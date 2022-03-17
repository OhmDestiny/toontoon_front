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
              <q-img class="col" src="~assets/naruto.png" />
              <div class="coverGap"></div>
              <q-img class="col" src="~assets/yaiba.png" />
              <div class="coverGap"></div>
              <q-img class="col" src="~assets/dragonball.png" />
            </div>
          </q-carousel-slide>
          <q-carousel-slide :name="2">
            <div class="row items-center">
              <q-img class="rounded-borders col" src="~assets/bleach.png" />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/tokyorevenger.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/attackontitan.png"
              />
            </div>
          </q-carousel-slide>
          <q-carousel-slide :name="3">
            <div class="row items-center">
              <q-img class="rounded-borders col" src="~assets/drstone.png" />
              <div class="coverGap"></div>
              <q-img class="rounded-borders col" src="~assets/onepiece.png" />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/jujutsukaisen.png"
              />
            </div>
          </q-carousel-slide>
          <q-carousel-slide :name="4">
            <div class="row items-center">
              <q-img class="rounded-borders col" src="~assets/myhero.png" />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/blackclover.png"
              />
              <div class="coverGap"></div>
              <q-img class="rounded-borders col" src="~assets/fireforce.png" />
            </div>
          </q-carousel-slide>
          <q-carousel-slide :name="5">
            <div class="row items-center">
              <q-img
                class="rounded-borders col"
                src="~assets/hunterxhunter.png"
              />
              <div class="coverGap"></div>
              <q-img
                class="rounded-borders col"
                src="~assets/onepunchman.png"
              />
              <div class="coverGap"></div>
              <q-img class="rounded-borders col" src="~assets/slime.png" />
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
