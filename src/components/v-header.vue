<template>
	<div class="header">
		<div class="sign">
			<a href="javascript:;">{{ reg }}</a> | <a href="javascript:;">{{ login }}</a>
		</div>
		<a href="javascript:;" class="down">{{ download }}</a>
	</div>
</template>

<script>
	export default {
		data (){
			return {
				reg: '注册',
				login: '登录',
				download: 'App下载'
			}
		}
	}
</script>

<style scoped>
	
.header {
  width: 100%;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-box-pack: justify;
      -ms-flex-pack: justify;
          justify-content: space-between;
  background: #fff url("//m.jr.jd.com/spe/qyy/main/images/jr-logo.png") no-repeat center center;
  background-size: auto 50%;
  padding: 0 0.3rem;
  position: fixed;
  left: 0;
  top: 0;
  z-index: 9;
}
.header .sign {
  height: 1rem;
  line-height: 1rem;
}
.header .sign a {
  font-size: 0.3rem;
  color: #666;
}
.header .down {
  width: 1.4rem;
  height: 0.65rem;
  background: #f04752;
  color: #fff;
  font-size: 0.3rem;
  text-align: center;
  line-height: 0.65rem;
  border-radius: 0.1rem;
}
</style>