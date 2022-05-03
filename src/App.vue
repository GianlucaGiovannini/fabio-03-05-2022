<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />
    <SiteFooter />
  </div>
</template>

<script>
import SiteHeader from "@/components/HeaderComponent.vue";
import SiteFooter from "@/components/FooterComponent.vue";
import SiteMain from "@/components/MainComponent.vue";

export default {
  name: "App",
  components: {
    SiteHeader,
    SiteFooter,
    SiteMain,
  }
};
</script>

<style lang="scss">
@import '@/assets/sass/style';


</style>
