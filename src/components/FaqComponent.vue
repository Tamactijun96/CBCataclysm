<template>
  <div class="d-flex justify-content-center">
    <div class="MainContainer">
      <div class="d-flex justify-content-center pt-5 mt-4">
        <h3>Buscar temas de ayuda</h3>
    </div>
    
    <h1>Preguntas frecuentes</h1>
    <div class="d-flex justify-content-center">
    <div class="accordion mr-5 MainContainer2" id="accordionExample2">
        <div class="card">
          <div class="card-header" id="headingOne2">
            <h2 class="mb-0">
              <button
                class="TitleCard btn btn-link btn-block text-left"
                type="button"
                data-toggle="collapse"
                data-target="#collapseOne2"
                aria-expanded="true"
                aria-controls="collapseOne2"
              >
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit beatae dolores corrupti!
              </button>
            </h2>
          </div>

          <div
            id="collapseOne2"
            class="collapse show"
            aria-labelledby="headingOne2"
            data-parent="#accordionExample2"
          >
            <div class="card-body DescriptionsCard">
             Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam nulla in quibusdam tenetur, vitae expedita reiciendis. Id voluptatum earum autem cupiditate dicta numquam commodi inventore qui. Fuga recusandae fugit cupiditate?
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingTwo2">
            <h2 class="mb-0">
              <button
                class="TitleCard btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#collapseTwo2"
                aria-expanded="false"
                aria-controls="collapseTwo2"
              >
               Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, esse.
              </button>
            </h2>
          </div>
          <div
            id="collapseTwo2"
            class="collapse"
            aria-labelledby="headingTwo2"
            data-parent="#accordionExample2"
          >
            <div class="card-body DescriptionsCard">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam, optio quidem, nam veritatis placeat nobis asperiores aliquam culpa minus facere voluptatum reiciendis maxime! Molestiae tempora magni cum aliquid maxime tenetur.
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingFour3">
            <h2 class="mb-0">
              <button
                class="TitleCard btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#collapseFour3"
                aria-expanded="false"
                aria-controls="collapseFour3"
              >
               Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam vero sapiente eveniet?
              </button>
            </h2>
          </div>
          <div
            id="collapseFour3"
            class="collapse"
            aria-labelledby="headingFour3"
            data-parent="#accordionExample2"
          >
            <div class="card-body DescriptionsCard">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Pariatur eveniet officia non vel neque mollitia hic laudantium reiciendis est, ipsa incidunt voluptas dolore repellendus accusantium quaerat corrupti ipsam nemo ea!
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingFive4">
            <h2 class="mb-0">
              <button
                class="TitleCard btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#collapseFive4"
                aria-expanded="false"
                aria-controls="collapseFive4"
              >
               Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur ipsum cupiditate quod ratione.
              </button>
            </h2>
          </div>
          <div
            id="collapseFive4"
            class="collapse"
            aria-labelledby="headingFive4"
            data-parent="#accordionExample2"
          >
            <div class="card-body DescriptionsCard">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, laboriosam. Perferendis possimus, molestias aperiam, sed fuga praesentium architecto error sequi mollitia magnam temporibus nam suscipit accusamus earum iste. Ratione, vero?
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header" id="headingThree6">
            <h2 class="mb-0">
              <button
                class="TitleCard btn btn-link btn-block text-left collapsed"
                type="button"
                data-toggle="collapse"
                data-target="#collapseThree6"
                aria-expanded="false"
                aria-controls="collapseThree6"
              >
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur consequuntur nemo fugiat?
              </button>
            </h2>
          </div>
          <div
            id="collapseThree6"
            class="collapse"
            aria-labelledby="headingThree6"
            data-parent="#accordionExample2"
          >
            <div class="card-body DescriptionsCard">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis quaerat explicabo molestias quas fuga quidem consectetur veniam nobis eaque vel, blanditiis reiciendis sunt obcaecati quia voluptates, architecto eligendi voluptatum error!
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "faqComponet",
};
</script>

<style scoped>
.MainContainer {
  border-top: 2px solid rgba(255, 255, 255, 0.2); /* Division de container */
  border-bottom: 2px solid rgba(255, 255, 255, 0.2); /* Division de container */
  width: 2600px;
  height: 1000px;
  background-image: url("@/assets/FAQs_Desktop.avif");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.MainContainer2 {
  width: 860px;
}

.TitleCard {
  color: #fff;
  font-family: "Quadrat Serial", serif;
 
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
