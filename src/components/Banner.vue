<template>
  <div>
    <div class="banners pt-5">
      <headers />
     <CataclysmBannerGroup 
     ChildTitle="Supera las adversidades" 
     ChildDescriptions="Cataclysm Classic se incluye en tu suscripción"
     />
      <div class="video-banner d-flex justify-content-center">
        <video
          src="../assets/[Cataclysm_Launch]_masthead.webm"
          no-ratio=""
          muted=""
          loop=""
          playsinline=""
          listening=""
        ></video>
      </div>
    </div>
  </div>
</template>

<script>
import Headers from "./Headers.vue";
import CataclysmBannerGroup from './CataclysmBannerGroup.vue'
export default {
  components: { Headers, CataclysmBannerGroup},
  name: "Banner",
};


</script>

<style scoped>

.banners {
  position: relative;
  margin-top: -60px;
  height: 1250px;
}

.video-banner {
  position: absolute;
  top: 0; 
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 0;
  mask-image: linear-gradient(to bottom, black 90%, transparent 100%);
}
</style>
