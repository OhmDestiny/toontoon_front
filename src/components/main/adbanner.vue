<template>
  <div>
    <!-- pc  -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    >
      <div class="bannerPc">
        <img src="~assets/adbanner.png" alt="" />
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
.bannerPc {
  margin: auto;
  height: 330px;
  width: 100%;
  max-width: 1400px;
}

.brx {
  border: 1px solid red;
}
</style>
