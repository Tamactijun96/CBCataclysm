<template>
  <div class="teste">
    <div class="mainContainer">
      <h1>Puede que también te guste</h1>

      <div class="d-flex d-block justify-content-center align-items-center p-5">
        <div class="card borderEffect" style="width: 20rem">
          <img
            class="card-img-top p-3"
            src="@/assets/card1.avif"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Wrath of the Lich King</h5>
            <p class="card-text">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit.
              Exercitationem nisi ducimus nesciunt necessitatibus, beatae
              libero?
            </p>
          </div>
        </div>
        <div class="card borderEffect" style="width: 20rem">
          <img
            class="card-img-top p-3"
            src="@/assets/card2.avif"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Cataclysm</h5>
            <p class="card-text">
              Lorem, ipsum dolor sit amet consectetur adipisicing elit. Impedit
              eius explicabo iusto labore ducimus tenetur.
            </p>
          </div>
        </div>
        <div class="card borderEffect" style="width: 20rem">
          <img
            class="card-img-top p-3"
            src="@/assets/card3.avif"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Mists of Pandaria</h5>
            <p class="card-text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus
              mollitia explicabo id ratione harum atque.
            </p>
          </div>
        </div>
        <div class="card borderEffect" style="width: 20rem">
          <img
            class="card-img-top p-3"
            src="@/assets/card4.avif"
            alt="Card image cap"
          />
          <div class="card-body">
            <h5 class="card-title">Ogame</h5>
            <p class="card-text">
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Tempora
              voluptates quod veritatis.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "faq",
  components: {},
};
</script>

<style scoped>

div.mainContainer {
  padding-top: 80px;
}

.teste {
  background: none;
}

div.card {
  height: 430px;
  margin: 20px;
  margin-bottom: 100px;
  background: linear-gradient(
      180deg,
      rgba(0, 0, 0, 0.3) 0%,
      rgba(0, 0, 0, 0) 39.51%
    ),
    rgba(61, 61, 61, 0.2);
  border: 2px solid rgba(56, 46, 44, 0.4);
}

div.card:hover {
  border-color: rgba(170, 36, 9, 0.7);
  filter: brightness(1.25);
  transition: ease-in-out 0.2s;
}

h5.card-title {
  margin-top: 18px;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  color: #fff;
  font-family: "Quadrat Serial", serif;
}

p.card-text {
  margin-top: 24px;
  color: #ffffffb3;
  letter-spacing: 0px;
  font-size: 16px;
  font-family: "Open Sans", serif;
}

.borderEffect::after {
  content: "";
  position: absolute;
  top: 5px;
  left: 5px;
  bottom: 245px;
  right: 5px;
  border: 22px solid;
  border-image: url("@/assets/Border-l.avif");
  border-image-slice: 22 22 fill;
  pointer-events: none;
  z-index: 1;
}


.borderEffect::after {
  content: "";
  position: absolute;
  top: 5px;
  left: 5px;
  bottom: 245px;
  right: 5px;
  border: 22px solid;
  border-image: url("@/assets/Border-l.avif");
  border-image-slice: 22 22 fill;
  pointer-events: none;
  z-index: 1;
}
</style>
