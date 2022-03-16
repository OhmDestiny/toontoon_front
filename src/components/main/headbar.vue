<template>
  <div>
    <!-- pc  -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    >
      <div class="bgHeadBar row items-center" align="center">
        <div class="col-1 brx">
          <img src="~assets/toontoonicon.png" alt="" style="width: 70px" />
        </div>
        <div style="width: 20px"></div>
        <div class="col-1 font18 textCategory">ชั้นหนังสือ</div>
        <div style="width: 20px"></div>
        <div class="col-1 font18 textCategory">ยอดนิยม</div>
        <div style="width: 20px"></div>
        <div class="col-1 font18 textCategory">การ์ตูนออกใหม่</div>
        <div style="width: 20px"></div>
        <div class="col-1 font18 textCategory">อ่านล่าสุด</div>
      </div>
    </div>

    <!-- tablet  -->
    <div class="mobile-only gt-xs"></div>

    <!-- mobile  -->
    <div class="mobile-only lt-sm"></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.bgHeadBar {
  margin: auto;
  background: #212121;
  height: 65px;
  width: 100%;
  max-width: 1400px;
}
.textCategory {
  color: #f6f7fb;
}
</style>
