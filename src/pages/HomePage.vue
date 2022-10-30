<template>
  <AboutUsComponent />
  <div class="activityMargin">
    <ActivityComponent />
  </div>
  <EthicsComponent />
  <FooterComponent />
</template>

<script>
import AboutUsComponent from "../components/layout/AboutUs/AboutUsComponent.vue";
import ActivityComponent from "../components/layout/Activity/ActivityComponent.vue";
import EthicsComponent from "../components/layout/Ethics/EthicsComponent.vue";
import FooterComponent from "../components/layout/Footer/FooterComponent.vue";

export default {
  components: {
    AboutUsComponent,
    ActivityComponent,
    EthicsComponent,
    FooterComponent,
  },
};
</script>

<style scoped>
.activityMargin {
  padding-top: 3rem;
}
</style>
