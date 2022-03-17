<template>
  <div>
    <!-- pc  -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    >
      <div class="">
        <q-carousel
          class="bgPromotoinBar"
          v-model="slide"
          transition-prev="slide-right"
          transition-next="slide-left"
          autoplay
          height="300px"
          swipeable
          infinite
          animated
          control-color="primary"
          navigation
        >
          <q-carousel-slide :name="1">
            <div class="row items-center">
              <q-img class="col" src="~assets/cover/naruto.png" />
              <div class="coverGap"></div>
              <q-img class="col" src="~assets/cover/yaiba.png" />
              <div class="coverGap"></div>
              <q-img class="col" src="~assets/cover/dragonball.png" />
            </div>
          </q-carousel-slide>
          -->
          <q-carousel-slide :name="2">
            <div class="row items-center">
              <q-img
                class="rounded-borders col"
                src="~assets/cover/bleach.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/tokyorevenger.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/attackontitan.png"
              />
            </div>
          </q-carousel-slide>
          <q-carousel-slide :name="3">
            <div class="row items-center">
              <q-img
                class="rounded-borders col"
                src="~assets/cover/drstone.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/onepiece.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/jujutsukaisen.png"
              />
            </div>
          </q-carousel-slide>
          <q-carousel-slide :name="4">
            <div class="row items-center">
              <q-img
                class="rounded-borders col"
                src="~assets/cover/myhero.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/blackclover.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/fireforce.png"
              />
            </div>
          </q-carousel-slide>
          <q-carousel-slide :name="5">
            <div class="row items-center">
              <q-img
                class="rounded-borders col"
                src="~assets/cover/hunterxhunter.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/onepunchman.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/cover/slime.png"
              />
            </div>
          </q-carousel-slide>
        </q-carousel>
      </div>
    </div>
    <!-- tablet  -->
    <div class="mobile-only gt-xs"></div>

    <!-- mobile  -->
    <div class="mobile-only lt-sm"></div>
  </div>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    return {
      slide: ref(1),
    };
  },
};
</script>

<style lang="scss" scoped>
.bgPromotoinBar {
  margin: auto;
  background: #212121;
  width: 100%;
  max-width: 1400px;
}
.coverGap {
  width: 20px;
}
</style>
