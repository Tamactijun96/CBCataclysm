<template>
    <div>
        <button class="ButtonBlizz pt-1" type="submit">
            {{ textButton }}
          </button>
    </div>
</template>


<script>
export default {
    name: 'ButtonHeaderOne',
    props: {
        textButton: String,
    } 
}
    
</script>


<style scoped>

.ButtonBlizz {
  font-weight: inherit;
  background-color: #761500;
  width: 137px;
  height: 49px;
  margin-right: 7px;
  letter-spacing: 0px;
  border: none;
  margin-top: 1px;
  border-radius: 8px;
  font-weight: 600;
  color: #ffffff;
  font-family: "Poppins", Helvetica, Arial, sans-serif;
  text-align: center;
  line-height: normal;
  transition: var(--transition-hover);
  font-size: 16px;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  align-items: center;
}

.ButtonBlizz:hover {
  background-color: #a01d00;
}
</style>