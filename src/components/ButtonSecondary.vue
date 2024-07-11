<template>
  <div>
    <button class="ButtonSecondary">
      {{ textButton }}
    </button>
  </div>
</template>
<script>
export default {
  name: "ButtonSecondary",
  props: ["textButton"],
};
</script>

<style scoped>
.ButtonSecondary {
  font-size: 24px;
  font-family: "Open Sans", serif;
  text-transform: uppercase;
  color: #f8b700;
  background: rgba(0, 0, 0, 0.3);
  border-width: 2px;
  border-style: solid;
  border-image: linear-gradient(#ffa800, #ff8a00) 1;
  border-radius: 0px;
  font-weight: 600;
  width: 290px;
  height: 74px;
  margin-bottom: 20px;
}

.ButtonSecondary:hover {
  background: linear-gradient(
      0deg,
      rgba(0, 0, 0, 0.1) 0%,
      rgba(0, 0, 0, 0.1) 100%
    ),
    rgba(255, 168, 0, 0.2);
}
</style>
