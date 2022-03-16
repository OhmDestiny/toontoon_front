<template>
  <div>
    <!-- pc  -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    >
      <div class="newcommerbg">
        <div class="row">
          <div class="col text q-pl-md">มาใหม่</div>
          <div class="col-1 text">เพิ่มเติม ></div>
        </div>
        <div class="row">
          <div class="mangabox" align="center">
            <img
              class="q-pt-md"
              src="~assets/bleach.png"
              alt="bleach"
              style="width: 225px"
            />
            <div class="subtext" align="light">
              Bleach <br />
              บลีซ เทพมรณะ
            </div>
          </div>
          <div class="imagegap"></div>
          <div class="mangabox" align="center">
            <img
              class="q-pt-md"
              src="~assets/bleach.png"
              alt="bleach"
              style="width: 225px"
            />
            <div class="subtext" align="light">
              Bleach <br />
              บลีซ เทพมรณะ
            </div>
          </div>
          <div class="imagegap"></div>
          <div class="mangabox" align="center">
            <img
              class="q-pt-md"
              src="~assets/bleach.png"
              alt="bleach"
              style="width: 225px"
            />
            <div class="subtext" align="light">
              Bleach <br />
              บลีซ เทพมรณะ
            </div>
          </div>
          <div class="imagegap"></div>
          <div class="mangabox" align="center">
            <img
              class="q-pt-md"
              src="~assets/bleach.png"
              alt="bleach"
              style="width: 225px"
            />
            <div class="subtext" align="light">
              Bleach <br />
              บลีซ เทพมรณะ
            </div>
          </div>
          <div class="imagegap"></div>
          <div class="mangabox" align="center">
            <img
              class="q-pt-md"
              src="~assets/bleach.png"
              alt="bleach"
              style="width: 225px"
            />
            <div class="subtext" align="light">
              Bleach <br />
              บลีซ เทพมรณะ
            </div>
          </div>
          <div class="imagegap"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.newcommerbg {
  margin: auto;
  background: #212121;
  height: 65px;
  width: 100%;
  max-width: 1400px;
}
.text {
  color: white;
  font-size: 24px;
  margin: auto;
}
.subtext {
  color: white;
  font-size: 16px;
}
.mangabox {
  background: #474747;
  width: 250px;
  height: 400px;
}
.imagegap {
  width: 10px;
}
</style>
