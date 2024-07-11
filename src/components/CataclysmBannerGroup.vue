<template>
  <div>
    <div class="CataclysmBannerGroup">
      <img class="logoCataclysm-md" :src="LogoBanner" alt="" />
      <div>
        <h2 class="CataclysmChildTitle">{{ ChildTitle }}</h2>
      </div>
      <div class="pt-1">
        <span class="CataclysmChildDescriptions">
          {{ ChildDescriptions }}
        </span>
      </div>
      <div class="ButtonBanner d-flex flex-inline">
        <ButtonPrimary
          textButton="Suscribirse"
          v-bind:style="{ marginRight: '22px' }"
        />
        <ButtonSecondary textButton="Comprar mejoras" />
      </div>
    </div>
  </div>
</template>

<script>
import ButtonPrimary from "./ButtonPrimary.vue";
import ButtonSecondary from "./ButtonSecondary.vue";

export default {
  name: "CataclysmBannerGroup",
  props: {
    LogoBanner: String,
    ChildTitle: String,
    ChildDescriptions: String,
  },
  components: {
    ButtonPrimary,
    ButtonSecondary,
  },
};
</script>

<style scoped>
.CataclysmBannerGroup {
  position: absolute;
  margin-left: 50%;
  padding-left: 123px;
  top: 160px;
  z-index: 1;
}

.CataclysmChildTitle {
  margin-left: 2px;
}

.ButtonBanner {
  margin-top: 38px;
}

span.CataclysmChildDescriptions {
  font-size: 20px;
  margin-top: 3px;
  padding-right: 6px;
  color: #ffffffb3;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  letter-spacing: 0px;
}

.logoCataclysm-md {
  width: 480px;
  height: 200px;
  margin-right: -3px;
  margin-top: -2px;
}
</style>
