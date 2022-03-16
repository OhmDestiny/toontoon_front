<template>
  <div>
    <!-- pc  -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    >
      <div class="bgHeadBar row" align="center">
        <div class="col-1">
          <q-img src="../../assets/tootoonicon.png" alt="" />
        </div>
        <div class="col-2"></div>
        <div class="col-2"></div>
        <div class="col-2"></div>
        <div class="col-2"></div>
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
</style>
