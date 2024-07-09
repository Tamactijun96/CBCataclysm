<template>
  <div class="teste">
    <div>
      <h1>Puede que también te guste</h1>
      <div class="d-flex d-block justify-content-center align-items-center p-5">
        <div class="card" style="width: 18rem">
          <img class="card-img-top" src="@/assets/card1.avif" alt="Card image cap" />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img class="card-img-top" src="@/assets/card2.avif" alt="Card image cap" />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img class="card-img-top" src="@/assets/card3.avif" alt="Card image cap" />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card" style="width: 18rem">
          <img class="card-img-top" src="@/assets/card4.avif" alt="Card image cap" />
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">
              Some quick example text to build on the card title and make up the
              bulk of the card's content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "faq",
};
</script>

<style scoped>

.teste {
  background: none;
}


div.card{
  margin: 20px;
  margin-bottom: 100px;
  background:linear-gradient(180deg, rgba(0, 0, 0, 0.3) 0%, rgba(0, 0, 0, 0) 39.51%), rgba(61, 61, 61, 0.2);
  border: 2px solid rgba(56, 46, 44, 0.4);
}
h5.card-title{
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  color: #fff;
  font-family: "Quadrat Serial", serif;
  
}

p.card-text{
  color: #ffffffb3;
  letter-spacing: 0px;
  font-size: 16px;
  font-family: "Open Sans", serif;
}

</style>
