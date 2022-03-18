<template>
  <div>
    <!-- pc  -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    >
      <div class="bgHeadBar row items-center" align="center">
        <div class="col-1 cursor-pointer">
          <img src="~assets/toontoonicon.png" alt="" style="width: 70px" />
        </div>
        <div style="width: 50px"></div>
        <div class="col-1 font18 textAllColor">ชั้นหนังสือ</div>
        <div style="width: 50px"></div>
        <div class="col-1 font18 textAllColor">ยอดนิยม</div>
        <div style="width: 50px"></div>
        <div class="col-1 font18 textAllColor">การ์ตูนออกใหม่</div>
        <div style="width: 50px"></div>
        <div class="col-1 font18 textAllColor">อ่านล่าสุด</div>
        <div class="col"></div>
        <div class="row textAllColor items-center" align="right">
          <q-input dark v-model="searchBar" dense style="width: 240px" />
          <q-icon size="20px " name="fa-solid fa-magnifying-glass" />
        </div>
        <div class="q-ma-md q-pt-xs" align="center">
          <div class="textAllColor font12 darkModeBox">Dark mode</div>
        </div>
      </div>
    </div>

    <!-- tablet  -->
    <div class="mobile-only gt-xs"></div>

    <!-- mobile  -->
    <div class="mobile-only lt-sm"></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      searchBar: "",
    };
  },
};
</script>

<style lang="scss" scoped>
.bgHeadBar {
  margin: auto;
  background: #212121;
  height: 65px;
  width: 100%;
  max-width: 1400px;
}
.bgLightIcon {
  cursor: pointer;
  width: 31px;
  height: 31px;
  background: #f6f7fb;
  border-radius: 10px;
}
.darkModeBox {
  cursor: pointer;
  width: 70px;
  height: 30px;
  line-height: 30px;
  border: 1px solid#f6f7fb;
  border-radius: 5px;
}
</style>
