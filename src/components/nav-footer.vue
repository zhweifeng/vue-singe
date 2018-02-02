<template>
    <div class="tab">
        <ul class="tab-list">
            <li class="tab-list-item">
                <router-link to="home" class="link-block">
                    <img src="//img12.360buyimg.com/jrpmobile/jfs/t3451/188/644771475/2428/800d7cb7/580f2435Nbfaa8055.png?width=66&amp;height=66">
                    <p>首页</p>
                </router-link>
            </li>
            <li class="tab-list-item">
                <router-link to="licai" class="link-block">
                    <img src="//img12.360buyimg.com/jrpmobile/jfs/t3811/55/345433999/2930/116d3dd1/580f1e25N028a1f2c.png?width=66&height=66">
                    <p>理财</p>
                </router-link>
            </li>
            <li class="tab-list-item">
                <router-link to="bai" class="link-block">
                    <img src="//img12.360buyimg.com/jrpmobile/jfs/t3343/179/621044750/1484/5af6b11a/580f50e4N005181d0.png?width=66&height=66">
                    <p>白条</p>
                </router-link>
            </li>
            <li class="tab-list-item">
                <router-link to="zhong" class="link-block">
                    <img src="//img12.360buyimg.com/jrpmobile/jfs/t3604/98/635506544/2317/443d3a51/580f240aNbee3dcc4.png?width=66&height=66">
                    <p>众筹</p>
                </router-link>
            </li>
        </ul>
    </div>
</template>
<script>
    export default {
        data() {
            return {
                
            }
        },
        methods:{

        }
    }
</script>

<style scoped>
	
.tab {
  width: 100%;
  position: fixed;
  bottom: 0;
  left: 0;
  background: #fff;
}
.tab .tab-list {
  width: 100%;
  height: 1.2rem;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -ms-flex-pack: distribute;
      justify-content: space-around;
}
.tab .tab-list .tab-list-item {
  text-align: center;
}
.tab .tab-list .tab-list-item a {
  display: block;
}
.tab .tab-list .tab-list-item a.router-link-active {
  color: #f00;
}
.tab .tab-list .tab-list-item a img {
  width: 0.5rem;
}
.tab .tab-list .tab-list-item a p {
  margin-top: 5px;
}
</style>



