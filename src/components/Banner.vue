<template>
  <div>
    <div class="banners pt-5">
      <headers></headers>
      <div class="CataclysmBannerGroup">
        <img class="logoCataclysm-md" src="@/assets/Kebab_Logo.avif" alt="" />
        <div>
          <h2 class="CataclysmChildTitle">Supera las adversidades</h2>
        </div>
        <div class="pt-1">
          <span class="CataclysmChildDescriptions">
            Cataclysm Classic se incluye en tu suscripción
          </span>
        </div>
        <div class="ButtonBanner d-flex flex-inline">
          <ButtonPrimary textButton="Suscribirse"></ButtonPrimary>
          <ButtonSecondary textButton="Comprar mejoras"></ButtonSecondary>
        </div>
      </div>

      <div class="video-banner d-flex justify-content-center">
        <video
          src="../assets/[Cataclysm_Launch]_masthead.webm"
          autoplay
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
import ButtonPrimary from "./ButtonPrimary.vue";
import ButtonSecondary from "./ButtonSecondary.vue";

export default {
  components: { Headers, ButtonPrimary, ButtonSecondary },
  name: "Banner",
};
</script>

<style scoped>

.logoCataclysm-md {
  width: 480px;
  height: 200px;
  margin-right: -3px;
  margin-top: -2px;
}

.CataclysmBannerGroup {
  position: absolute;
  margin-left: 50%;
  padding-left: 123px;
  top: 160px;
  z-index: 1;
}
.CataclysmChildTitle{
  margin-left: 2px;
}


span.CataclysmChildDescriptions {
  font-size: 20px;
  margin-top: 3px;
  padding-right: 6px;
  color: #ffffffb3;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  letter-spacing: 0px;
}

.ButtonBanner {
  margin-top: 38px;
}

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
