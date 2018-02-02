<template>
    <div>
        <v-swiper :swiperItem="swiperList"></v-swiper>
        <div class="middle">
            我是白条内容
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
                    '//img12.360buyimg.com/jrpmobile/jfs/t8491/303/504628479/60643/100648de/59a94358N92475fca.jpg?width=750&height=320',
                    '//img12.360buyimg.com/jrpmobile/jfs/t8437/321/1758527686/40952/f66d552f/59bf1f41N50d846f9.jpg?width=750&height=320'
                ]
            }
        },
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