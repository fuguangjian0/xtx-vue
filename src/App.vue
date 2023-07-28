<template>
  <div id="app">
    <XtxShortCut></XtxShortCut>
    <XtxHeaderNav></XtxHeaderNav>
    <XtxBanner></XtxBanner>
    <XtxNewGoods></XtxNewGoods>
    <XtxHotBrand></XtxHotBrand>
    <XtxTopic></XtxTopic>
    <XtxFooter></XtxFooter>
  </div>
</template>

<script>


import XtxShortCut from "@/components/XtxShortCut.vue";
import XtxHeaderNav from "@/components/XtxHeaderNav.vue";
import XtxBanner from "@/components/XtxBanner.vue";
import XtxNewGoods from "@/components/XtxNewGoods.vue";
import XtxHotBrand from "@/components/XtxHotBrand.vue";
import XtxTopic from "@/components/XtxTopic.vue";
import XtxFooter from "@/components/XtxFooter.vue";

export default {
  name: 'App',
  components: {
    XtxFooter,
    XtxTopic,
    XtxHotBrand,
    XtxNewGoods,
    XtxBanner,
    XtxHeaderNav,
    XtxShortCut

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
