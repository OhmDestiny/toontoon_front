<template>
  <div>
    <head-bar></head-bar>
    <promotion></promotion>
    <manga-box-new-comer></manga-box-new-comer>
    <continue-reading-box></continue-reading-box>
    <ad-banner></ad-banner>
    <popular-box></popular-box>
    <tag></tag>
    <preview-box></preview-box>
  </div>
</template>

<script>
import headBar from "../components/main/headbar.vue";
import adBanner from "../components/main/adbanner.vue";
import promotion from "../components/main/promotion.vue";
import mangaBoxNewComer from "../components/main/mangaboxnewcomer.vue";
import continueReadingBox from "../components/home/continuereadingbox.vue";
import popularBox from "../components/home/popularbox.vue";
import tag from "../components/main/tag.vue";
import previewBox from "../components/home/previewbox.vue";
export default {
  components: {
    headBar,
    adBanner,
    promotion,
    mangaBoxNewComer,
    continueReadingBox,
    popularBox,
    tag,
    previewBox,
  },
};
</script>

<style lang="scss" scoped></style>
