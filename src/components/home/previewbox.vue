<template>
  <div>
    <!-- pc -->
    <div
      class="desktop-only shadow-6"
      style="max-width: 1600px; width: 100%; margin: auto"
    >
      <div class="previewBG q-pt-md">
        <div class="row gt-md">
          <div class="mangaBookBox" align="center">
            <img
              class="q-pt-md"
              src="~assets/previewpicture/reincarnationofthesuicidalbattlegod.png"
              alt="Reincarnation of the Suicidal Battle God"
              style="height: 330px"
            />
            <div class="subtext q-pl-md" align="center">
              Reincarnation of the <br />
              Suicidal Battle God
            </div>
          </div>
          <div class="imagegap"></div>
          <div class="mangaBookBox" align="center">
            <img
              class="q-pt-md"
              src="~assets/previewpicture/solospellcaster.png"
              alt="Solo Spell Caster"
              style="height: 330px"
            />
            <div class="subtext q-pl-md" align="center">Solo Spell Caster</div>
          </div>
          <div class="imagegap"></div>
          <div class="mangaBookBox" align="center">
            <img
              class="q-pt-md"
              src="~assets/previewpicture/rankerwholivesasecondtime.png"
              alt="Ranker Who Lives A Second Time"
              style="height: 330px"
            />
            <div class="subtext q-pl-md" align="center">
              Ranker Who Lives <br />
              A Second Time
            </div>
          </div>
          <div class="imagegap"></div>
          <div class="mangaBookBox" align="center">
            <img
              class="q-pt-md"
              src="~assets/previewpicture/peerlessdad.png"
              alt="Peerless Dad"
              style="height: 330px"
            />
            <div class="subtext q-pl-md" align="center">Peerless Dad</div>
          </div>
          <div class="imagegap"></div>
          <div class="mangaBookBox" align="center">
            <img
              class="q-pt-md"
              src="~assets/previewpicture/returnofthemountainhuasect.png"
              alt="Return of the Mountain Hua Sect"
              style="height: 330px"
            />
            <div class="subtext q-pl-md" align="center">
              Return of the Mountain <br />Hua Sect
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.previewBG {
  margin: auto;
  background: black;
  height: 435px;
  width: 100%;
  max-width: 1400px;
}
.mangaBookBox {
  width: 20%;
  height: 400px;
  background: #474747;
  width: 250px;
  height: 400px;
  cursor: pointer;
}
.subtext {
  color: white;
  font-size: 18px;
}
.imagegap {
  width: 36px;
}
.tablegap {
  height: 25px;
}
</style>
