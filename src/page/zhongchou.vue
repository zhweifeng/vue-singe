<template>
    <div>
        <v-swiper :swiperItem="swiperList"></v-swiper>
        <div class="middle">
            我是众筹内容
        </div>
    </div>
</template>
<script>
    import vSwiper from '../components/swiper'
    export default {
        components:{
            vSwiper
        },
        data() {
            return {
                swiperList:[
                    '//img12.360buyimg.com/jrpmobile/jfs/t3406/210/2247820735/50952/86016eea/5846d8e7N20446dbd.png?width=750&height=200',
                    '//img12.360buyimg.com/jrpmobile/jfs/t3739/82/2244582797/54399/746c7d79/5846a953N66b67d05.png?width=750&height=200',
                    '//img12.360buyimg.com/jrpmobile/jfs/t3214/113/4408032436/61548/ce316eef/5846d310Ne93f00c9.png?width=750&height=200'
                ]
            }
        }
    }
</script>
<style scoped>
    .middle{
    	height: 5rem;
    	text-align: center;
    	line-height: 5rem;
    	font-size: .8rem;
    	color: red;
    }
</style>