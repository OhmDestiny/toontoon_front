<template>
  <div>
    <div class="bannerPC">
      <div class="row">
        <div class="col-1">
          <div class="col" align="center">
            <img
              src="~assets/Adbanner.png"
              alt="finnbetbanner"
              width="1400px"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- mobile  -->
    <div class="mobile-only lt-sm">
      <div class="row">
        <div class="col-1">
          <div class="col" align="center">
            <img
              src="~assets/Adbanner.png"
              alt="finnbetbanner"
              width="1400px"
            />
          </div>
        </div>
      </div>
    </div>
    <!-- tablet  -->
    <div class="mobile-only gt-xs"></div>
    <!-- pc  -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    ></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.bannerPC {
  margin: auto;
  height: 65px;
  width: 1400px;
}

.brx {
  border: 1px solid red;
}
</style>
