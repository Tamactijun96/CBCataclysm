<template>
  <div class="d-flex justify-content-center">
    <div class="footer-backg">
      <h4>Mantente al día</h4>
      <div class="d-flex justify-content-center pt-4 mt-3">
        <i
          class="iconmain fa fa-facebook-official fa-x2 mt-4"
          aria-hidden="true"
        ></i>
        <i class="iconmain fa fa-youtube fa-x5 mt-4" aria-hidden="true"></i>
        <i class="iconmain fab fa-discord mt-4" aria-hidden="true"></i>
        <i class="iconmain fa fa-instagram mt-4" aria-hidden="true"></i>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "foot",
};
</script>

<style scoped>
.footer-backg {
  height: 600px;
  width: 2600px;
  background: url("@/assets/Footer_Desktop.avif") no-repeat;
  background-size: cover;
  border-top: 2px solid rgba(255, 255, 255, 0.2); /* Division de container */
}

i.iconmain {
  font-size: 44px;
  margin: 14px;
  color: #ffffffb3;
}
</style>
