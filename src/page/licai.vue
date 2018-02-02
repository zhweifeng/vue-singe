<template>
    <div>
        <v-swiper :swiperItem="swiperList"></v-swiper>
        <div class="middle">
            我是理财内容
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
                    '//img12.360buyimg.com/jrpmobile/jfs/t11149/181/856008463/68797/dc303e9/59f97baeN3cdae084.jpg?width=750&height=400',
                    '//img12.360buyimg.com/jrpmobile/jfs/t9994/205/2575467053/189117/125e7b05/59f97c36N7599be57.png?width=750&height=400'
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