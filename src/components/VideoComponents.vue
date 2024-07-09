<!-- Componente del video de la segunda seccion -->
<template>
  <div class="col videoImgOverlay">
    <img class="videoImg" src="../assets/LaunchTrailer_Thumbnail.jpg" alt="" />
  </div>
</template>

<script>
export default {
  name: "videoComponent",
};
</script>

<style scoped>

.videoImg {
  width: 870px;
  height: 500px;
  margin-left: -79px;
  margin-bottom: -34px;
  margin-top: -79px;
  margin-right: -34px;
}

.videoImgOverlay {
  text-align: left;
  padding: 80px;
}

.videoImgOverlay::after {
  content: "";
  position: absolute;
  top: -11px;
  left: -11px;
  bottom: 0;
  right: 0;
  border: 22px solid;
  border-image: url("../assets/Border-l.avif");
  border-image-slice: 22 22 fill;
  pointer-events: none;
  width: calc(100% - 22px);
  height: calc(100% - 22px);
  z-index: 1;
}
.videoImgOverlay:hover {
  filter: brightness(1.25);
  transition: ease-in-out 0.2s;
}

</style>