<template>
  <div class="d-flex justify-content-center">
    <div class="ShitMask">
      <header class="d-flex justify-content-center">
        <div class="FeaturesHeader">
          <h1>Características reseñables</h1>
          <p class="FeaturesInfo">
            Tras la aparición de Alamuerte el Destructor, que dejó una herida
            abierta en el tejido de Azeroth, se ha llamado de nuevo a los héroes
            para que vivan una Azeroth reforjada por completo y la defiendan de
            la devastación absoluta.
          </p>
        </div>
      </header>

      <section>
        <div class="container d-flex justify-content-center pt-5 mt-3">
          <div>
            <ul class="list-unstyled">
              <li class="media">
                <div class="imagesFeaturesList mr-2">
                  <img
                    class="mr-3 imagesFeaturesListItem"
                    src="../assets/Goblins&Worgen_icon.avif"
                    alt="Generic placeholder image"
                  />
                </div>
                <div class="media-body">
                  <h5 class="mt-0 mb-1 Feature-title-item">
                    Goblins y huargen
                  </h5>
                  <p class="FeatureDescriptions">
                    Explora siete zonas nuevas y tres zonas iniciales para las
                    dos nuevas razas, los goblins y los huargen. Todas ellas
                    están repletas de contenido cataclísmico que reavivará tus
                    ganas de aventura.
                  </p>
                </div>
              </li>
              <li class="media my-4">
                <div class="imagesFeaturesList mr-2">
                  <img
                    class="mr-3 imagesFeaturesListItem"
                    src="../assets/NewLevelCap_icon.avif"
                    alt="Generic placeholder image"
                  />
                </div>
                <div class="media-body">
                  <h5 class="mt-0 mb-1 Feature-title-item">
                    Nuevo límite de nivel
                  </h5>
                  <p class="FeatureDescriptions">
                    Sube a nuevas cotas de poder mientras defiendes Azeroth y
                    aprende nuevos talentos en tu aventura hasta el nivel 85.
                  </p>
                </div>
              </li>
              <li class="media">
                <div class="imagesFeaturesList mr-2">
                  <img
                    class="mr-3 imagesFeaturesListItem"
                    src="../assets/CustomizeYourCharacter_icon.avif"
                    alt="Generic placeholder image"
                  />
                </div>
                <div class="media-body">
                  <h5 class="mt-0 mb-1 Feature-title-item">
                    Personaliza tu personaje
                  </h5>
                  <p class="FeatureDescriptions">
                    Mejora todavía más tu apariencia con el sistema de
                    transfiguraciones. Personaliza la apariencia de algunas
                    armas y armaduras sin modificar sus estadísticas.
                  </p>
                </div>
              </li>
            </ul>
          </div>
          <div>
            <ul class="list-unstyled">
              <li class="media">
                <div class="imagesFeaturesList mr-2">
                  <img
                    class="mr-3 imagesFeaturesListItem"
                    src="../assets/Dungeons&Raids_icon.webp"
                    alt="Generic placeholder image"
                  />
                </div>
                <div class="media-body">
                  <h5 class="mt-0 mb-1 Feature-title-item">
                    Nuevas mazmorras y bandas
                  </h5>
                  <p class="FeatureDescriptions">
                    Los valientes defensores de Azeroth podrán luchar en siete
                    trepidantes mazmorras y cuatro nuevas bandas cataclísmicas.
                  </p>
                </div>
              </li>
              <li class="media my-4">
                <div class="imagesFeaturesList mr-2">
                  <img
                    class="mr-3 imagesFeaturesListItem"
                    src="../assets/ElementalPlanes_icon.avif"
                    alt="Generic placeholder image"
                  />
                </div>
                <div class="media-body">
                  <h5 class="mt-0 mb-1 Feature-title-item">
                    Conquista los planos elementales
                  </h5>
                  <p class="FeatureDescriptions">
                    Alamuerte ha dañado la franja entre el plano mortal y el
                    elemental, y ahora Azeroth se enfrenta a una invasión de
                    elementales caóticos. ¡Debes detenerlo!
                  </p>
                </div>
              </li>
              <li class="media">
                <div class="imagesFeaturesList mr-2">
                  <img
                    class="mr-3 imagesFeaturesListItem"
                    src="../assets/ExpansiveZones_icon.avif"
                    alt="Generic placeholder image"
                  />
                </div>
                <div class="media-body">
                  <h5 class="mt-0 mb-1 Feature-title-item">Zonas amplias</h5>
                  <p class="FeatureDescriptions">
                    Explora siete zonas nuevas y tres zonas iniciales para las
                    dos razas nuevas, los goblins y los huargen. Están repletas
                    de contenido cataclísmico que reavivará tus ganas de
                    aventura.
                  </p>
                </div>
              </li>
            </ul>
          </div>
        </div>
        <div class="d-flex justify-content-center">
          <div class="FeaturesHeader">
            <h3 class="d-flex justify-content-center">
              Actualizaciones y mejoras
            </h3>
            <h1>Reaviva el fuego</h1>
            <p class="FeaturesInfo">
              Los jugadores de Classic podrán jugar de nuevo a esta emblemática
              expansión con una cadencia de contenido más rápida, mejoras en la
              subida de nivel, una interfaz de colecciones ampliada, un nuevo
              nivel de dificultad, añadido al buscador de grupos de mazmorra
              tras el lanzamiento de Cataclysm Classic, y muchas cosas más.
            </p>
          </div>
        </div>
      </section>
      <div class="container">
        <CollapseBlizz></CollapseBlizz>
      </div>
    </div>
  </div>
</template>

<script>
import CollapseBlizz from "./Collapse.vue";

export default {
  name: "Characteristics",
  components: {
    CollapseBlizz,
  },
};
</script>

<style scoped>
.ShitMask {
  background-image: url("../assets/Features_Desktop.avif"); /* Imagen de lava como fondo */
  background-repeat: no-repeat;
  background-size: cover;
  width: 2600px;
  mask-image: url("../assets/features-mask-image-v5.png");
  -webkit-mask-box-image: url("../assets/features-mask-image-v5.png");
  mask-border-slice: 60 1200 fill;
}

.FeaturesHeader {
  margin-top: 150px;
}

.FeaturesInfo {
  padding-top: 24px;
  width: 740px;
  color: #ffffffb3;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  letter-spacing: 1px;
  font-size: 19px;
}

.imagesFeaturesListItem {
  border-radius: 100%;
  width: 70px;
  height: 70px;
}

.imagesFeaturesList {
  border-radius: 100%;
  width: 80px;
  height: 80px;
  padding: 3px;
  position: relative;
}

.imagesFeaturesList::before {
  content: "";
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  height: 90%;
  width: 90%;
  border: 2px solid #ff4c24;
  border-radius: 100%;
  box-shadow: inset 0px 0px 20px 5px #000, 0px 0px 20px 10px #000;
}

.imagesFeaturesList::after {
  content: "";
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  height: 100%;
  width: 100%;
  padding: 5px;
  border: 1px solid #ffb800;
  border-radius: 100%;
}

.Feature-title-item {
  color: #fff;
  font-family: "Quadrat Serial", serif;
  text-align: left;
}

.FeatureDescriptions {
  text-align: left;
  margin-top: 15px;
  color: #ffffffb3;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  font-family: "Open Sans", Arial, Helvetica, sans-serif;
}
</style>
