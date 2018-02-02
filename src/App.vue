<template>
    <div id="app">
        <v-header></v-header>
        <router-view class="wrap-box"></router-view>
        <v-footer></v-footer>
        <nav-footer></nav-footer>
    </div>
</template>

<script>
    import vHeader from './components/v-header'
    import vFooter from './components/v-footer'
    import navFooter from './components/nav-footer'

    export default {
        name: 'App',
        components: {
            vHeader,
            vFooter,
            navFooter
        }
    }
</script>

<style>
    
html,
body {
  line-height: 1;
  font-weight: 200;
  font-family: Helvetica, Arial, "PingFang SC", "Hiragino Sans GB", "Heiti SC", "Microsoft YaHei", "WenQuanYi Micro Hei", sans-serif;
}
a {
  outline: none;
  -webkit-tap-highlight-color: rgba(0,0,0,0);
}
@media (-webkit-min-device-pixel-ratio: 1.5), (min-device-pixel-ratio: 1.5), (min--moz-device-pixel-ratio: 1.5) {
.border-1px::after {
    -webkit-transform: scaleY(0.7);
    transform: scaleY(0.7);
}
}
@media (-webkit-min-device-pixel-ratio: 2), (min-device-pixel-ratio: 2), (min--moz-device-pixel-ratio: 1.5) {
.border-1px::after {
    -webkit-transform: scaleY(0.5);
    transform: scaleY(0.5);
}
}
.clearfix::after {
  content: '.';
  display: block;
  height: 0;
  line-height: 0;
  clear: both;
  visibility: hidden;
}
.wrap-box {
  width: 100%;
  margin-top: 1.2rem;
}
</style>
