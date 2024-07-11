<template>
  <div>
    <button class="ButtonPrimary">{{ textButton }}</button>
  </div>
</template>

<script>
export default {
  name: "ButtonPrimary",
  props: ["textButton"],
};
</script>

<style scoped>
.ButtonPrimary {
  color: #fff;
  font-size: 24px;
  font-family: "Open Sans", serif;
  text-transform: uppercase;
  background: linear-gradient(180deg, #aa2409, #761500 100%);
  border-width: 2px;
  border-style: solid;
  border-image: linear-gradient(#f94119, #f83c00, #f94119) 1;
  border-radius: 0px;
  font-weight: 600;
  width: 240px;
  height: 74px;
}

.ButtonPrimary:hover {
  background: rgba(249, 65, 25, 0.7);
}
</style>
