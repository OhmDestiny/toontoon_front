<template>
  <div class="mainBg">
    <head-bar></head-bar>
    <promotion></promotion>
    <manga-box-new-comer></manga-box-new-comer>
    <continue-reading-box></continue-reading-box>
    <ad-banner></ad-banner>
    <popular-box></popular-box>
    <div class="row items-center textAllColor rowBox">
      <div class="font24 col-11">หมวดหมู่</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
      <tag></tag>
    </div>
    <div>
      <ad-banner></ad-banner>
    </div>

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

<style lang="scss" scoped>
.mainBg {
  background: #121212;
}
.rowBox {
  margin: auto;
  max-width: 1400px;
  width: 100%;
}
</style>
