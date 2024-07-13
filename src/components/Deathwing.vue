<template>
  <div class="fcontainer">
    <div class="death d-flex justify-content-center flex-column">
      <div class="GamePack">
        <h3 class="d-flex justify-content-center">
          Sube la temperatura a tu experiencia
        </h3>
        <h1>Packs del juego</h1>
        <div class="tt d-flex justify-content-center">
          <p class="FeaturesInfo">
            Para jugar a Cataclysm Classic¹ solo se requiere una suscripción a
            WoW® o tiempo de juego. No obstante, existen packs ígneos opcionales
            que ofrecen todo un surtido de objetos poco comunes para encender la
            chispa de tus aventuras.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "deathwing",
};
</script>

<style scoped>
.death {
  margin-top: 15px;
  background-image: url("../assets/deathwing.avif");
  background-repeat: no-repeat;
  background-position: center;
}

.GamePack {
  margin-top: 750px;
    
}


.FeaturesInfo {
  padding-top: 24px;
  width: 740px;
  color: #ffffffb3;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  letter-spacing: 1px;
  font-size: 19px;
}

.fcontainer {
  padding-top: 110px;
  margin-top: -170px;
}
</style>
