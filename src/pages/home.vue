<template>
  <div class="mainBg">
    <head-bar></head-bar>
    <promotion></promotion>
    <div class="row items-center textAllColor rowBox q-pt-md">
      <div class="font24 col-11">มาใหม่</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
    </div>
    <manga-box-new-comer></manga-box-new-comer>
    <div class="row items-center textAllColor rowBox q-pt-md">
      <div class="font24 col-11">อ่านต่อ</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
    </div>
    <continue-reading-box></continue-reading-box>
    <div class="q-pt-md">
      <ad-banner></ad-banner>
    </div>
    <div class="row items-center textAllColor rowBox q-pt-xl">
      <div class="font24 col-11">ยอดนิยม</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
    </div>
    <popular-box></popular-box>

    <div class="row items-center textAllColor rowBox q-pt-md">
      <div class="font24 col-11">หมวดหมู่</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
    </div>
    <div class="q-pt-sm">
      <tag></tag>
    </div>
    <div class="row items-center textAllColor rowBox q-pt-xl">
      <div class="font24 col-11">แฟนตาซี</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
    </div>

    <preview-box></preview-box>
    <div class="row items-center textAllColor rowBox q-pt-md">
      <div class="font24 col-11">ต่อสู้</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
    </div>
    <preview-box></preview-box>
    <div class="row items-center textAllColor rowBox q-pt-md">
      <div class="font24 col-11">โรแมนติก</div>
      <div class="font14 col" align="right">เพิ่มเติม ></div>
    </div>
    <preview-box></preview-box>
    <div class="q-pt-xl">
      <ad-banner></ad-banner>
    </div>
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
