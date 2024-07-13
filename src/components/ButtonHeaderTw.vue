<template>
  <div>
    <button class="ButtonBlizz pt-1" type="submit">
      {{ textButton }}
    </button>
  </div>
</template>

<script>
export default {
  name: "ButtonHeaderTwo",
  props: {
    textButton: String,
  },
};
</script>

<style scoped>
.ButtonBlizz {
  font-weight: inherit;
  background-color: #000000;
  width: 194px;
  height: 49px;
  letter-spacing: 0px;
  margin-left: 10px;
  margin-right: -5px;
  margin-top: 1px;
  border: none;
  border-radius: 8px;
  font-weight: 600;
  color: #ffffff;
  font-family: "Poppins", Helvetica, Arial, sans-serif;
  text-align: center;
  line-height: normal;
  transition: var(--transition-hover);
  font-size: 16px;
  overflow: hidden;
  outline: none;
  text-overflow: ellipsis;
  white-space: nowrap;
  align-items: center;
}

.ButtonBlizz:hover {
  background-color: #151515;
}
</style>
