<template>
  <div>
    <head-bar></head-bar>
    <ad-banner></ad-banner>
  </div>
</template>

<script>
import headBar from "../components/main/headbar.vue";
import adBanner from "../components/main/adbanner.vue";
export default {
  components: {
    headBar,
    adBanner,
  },
};
</script>

<style lang="scss" scoped></style>
