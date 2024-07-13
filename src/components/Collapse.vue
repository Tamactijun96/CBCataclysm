<template>
  <div class="MainContainer d-flex justify-content-center pt-3 mt-2">
    <div class="accordion mr-5" id="accordionExample">
      <div class="card">
        <div class="card-header" id="headingOne">
          <h2 class="mb-0">
            <button
              class="TitleCard btn btn-link btn-block text-left"
              type="button"
              data-toggle="collapse"
              data-target="#collapseOne"
              aria-expanded="true"
              aria-controls="collapseOne"
            >
              Experiencia de subida de nivel mejorada
            </button>
          </h2> 
        </div>

        <div
          id="collapseOne"
          class="collapse show"
          aria-labelledby="headingOne"
          data-parent="#accordionExample"
        >
          <div class="card-body DescriptionsCard">
            Asciende a nuevas cotas de poder con una experiencia de subida de
            nivel más fluida y acelerada.
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header" id="headingTwo">
          <h2 class="mb-0">
            <button
              class="TitleCard btn btn-link btn-block text-left collapsed"
              type="button"
              data-toggle="collapse"
              data-target="#collapseTwo"
              aria-expanded="false"
              aria-controls="collapseTwo"
            >
              Nuevo sistema de dificultad de mazmorras
            </button>
          </h2>
        </div>
        <div
          id="collapseTwo"
          class="collapse"
          aria-labelledby="headingTwo"
          data-parent="#accordionExample"
        >
          <div class="card-body DescriptionsCard">
            Tras el lanzamiento, se añadirá un nuevo sistema de dificultad de
            mazmorras que aportará oportunidades de mayor exigencia y
            complejidad para conseguir poderosas recompensas.
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header" id="headingFour">
          <h2 class="mb-0">
            <button
              class="TitleCard btn btn-link btn-block text-left collapsed"
              type="button"
              data-toggle="collapse"
              data-target="#collapseFour"
              aria-expanded="false"
              aria-controls="collapseFour"
            >
              Encuentra amigos nuevos con más facilidad
            </button>
          </h2>
        </div>
        <div
          id="collapseFour"
          class="collapse"
          aria-labelledby="headingFour"
          data-parent="#accordionExample"
        >
          <div class="card-body DescriptionsCard">
            El buscador de grupos de mazmorra ofrecerá un modo más sólido de
            reclutar compañeros, hacer cola y establecer conexiones.
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header" id="headingFive">
          <h2 class="mb-0">
            <button
              class="TitleCard btn btn-link btn-block text-left collapsed"
              type="button"
              data-toggle="collapse"
              data-target="#collapseFive"
              aria-expanded="false"
              aria-controls="collapseFive"
            >
              Monturas, mascotas y transfiguraciones para toda la cuenta
            </button>
          </h2>
        </div>
        <div
          id="collapseFive"
          class="collapse"
          aria-labelledby="headingFive"
          data-parent="#accordionExample"
        >
          <div class="card-body DescriptionsCard">
            Todos tus personajes podrán seguir compartiendo aventuras, con
            monturas y mascotas para toda la cuenta. Ahora podrán compartir una
            colección de transfiguraciones seleccionadas con el máximo cuidado.
          </div>
        </div>
      </div>
      <div class="card">
        <div class="card-header" id="headingThree">
          <h2 class="mb-0">
            <button
              class="TitleCard btn btn-link btn-block text-left collapsed"
              type="button"
              data-toggle="collapse"
              data-target="#collapseThree"
              aria-expanded="false"
              aria-controls="collapseThree"
            >
              Casa de subastas optimizada
            </button>
          </h2>
        </div>
        <div
          id="collapseThree"
          class="collapse"
          aria-labelledby="headingThree"
          data-parent="#accordionExample"
        >
          <div class="card-body DescriptionsCard">
            Llega un sistema actualizado para la casa de subastas que ofrece una
            experiencia optimizada para aquellos que quieren comprar y vender
            los suministros y el equipo de la mejor calidad.
          </div>
        </div>
      </div>
    </div>
    <div>
      <imgComponent />
    </div>
  </div>
</template>

<script>
import imgComponent from './ImgComponents.vue'

export default {
  components:{imgComponent},
  name: "CollapseBlizz",
};
</script>

<style scoped>

.MainContainer {
  padding-bottom: 345px;
}

.TitleCard {
  color: #fff;
  font-family: "Quadrat Serial", serif;
  text-align: left;
  font-size: 22px;
  text-decoration: none;
  margin-left: -30px;
  margin-top: -24px;
  padding-bottom: 12px;
}

.TitleCard:focus {
  color: #fdaf29;
}
.DescriptionsCard {
  color: #ffffffb3;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  letter-spacing: 1px;
  font-size: 19px;
  text-align: start;
  margin-left: -16px;
}

div.card {
  background: transparent;
  border: none;
  border-bottom: #ffffff23 3px solid;
  border-radius: 0px;
}

div.card-header {
  border: none;
  background: none;
}

</style>
