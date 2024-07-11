<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light BlizzNavbar">
      <a class="navbar-brand" href="#"
        ><img class="logo" src="../assets/rogwow_logo_126x41.png" alt=""
      /></a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <!-- Mini logo Cataclysm -->

        <MiniLogoCataclysm></MiniLogoCataclysm>

        <!-- End Mini logo Cataclysm -->

        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link nav-nm" href="#"
              ><span class="nav-nm-text text-white p-1">Resumen</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link text-white nav-nm ml-1" href="#"
              ><span class="nav-nm-text text-white p-1"
                >Características</span
              ></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link text-white nav-nm ml-1" href="#"
              ><span class="nav-nm-text text-white p-1"
                >Mejoras del juego</span
              ></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link text-white nav-nm ml-1" href="#"
              ><span class="nav-nm-text text-white p-1"
                >Preguntas frecuentes</span
              ></a
            >
          </li>
        </ul>
        <li class="nav-item dropdown list-account">
          <a
            class="ButtonAccount nav-link dropdown-toggle pt-3"
            href="#"
            id="navbarDropdown"
            role="button"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
          >
            <i class="fa fa-user-o fa-gray pr-3" aria-hidden="true"></i>Cuenta
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item access-background" href="#"
              ><button class="btn-access" type="submit">
                Iniciar sesión
              </button></a
            >
            <a class="dropdown-item dropdown-myitem" href="#"
              ><i class="fa fa-cogs fa-gray pr-2" aria-hidden="true"></i>Ajustes
              de tu cuenta</a
            >
            <a class="dropdown-item dropdown-myitem" href="#"
              ><i
                class="fa fa-pencil-square-o fa-gray pr-2"
                aria-hidden="true"
              ></i
              >Inscribirse</a
            >
            <a class="dropdown-item dropdown-myitem" href="#"
              ><i
                class="fa fa-question-circle-o fa-gray pr-2"
                aria-hidden="true"
              ></i
              >Asistencia</a
            >
            <a class="dropdown-item dropdown-myitem" href="#"
              ><i class="fa fa-shopping-bag fa-gray pr-2" aria-hidden="true"></i
              >Tienda</a
            >
            <a class="dropdown-item dropdown-myitem" href="#"
              ><i class="fa fa-download fa-gray pr-2" aria-hidden="true"></i
              >Descarga Launcher</a
            >
          </div>
        </li>
        <form class="form-inline">
          <ButtonHeaderOne textButton="Suscribirse" />
          <ButtonHeaderTwo textButton="Comprar mejoras" />
        </form>
      </div>
    </nav>
  </div>
</template>

<script>
import MiniLogoCataclysm from "./MiniLogoCataclysm.vue";
import ButtonHeaderTwo from "./ButtonHeaderTw.vue";
import ButtonHeaderOne from "./ButtonHeaderOne.vue";

export default {
  components: { MiniLogoCataclysm, ButtonHeaderOne, ButtonHeaderTwo },
  name: "Headers",
};
</script>

<style scoped>
.BlizzNavbar {
  position: fixed;
  top: 16px;
  left: 16px;
  right: 16px;
  background-color: rgba(34, 13, 11, 0.8);
  height: 70px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 2;
  max-width: 2500px;
  margin: 0 auto;
}

.logo {
  padding: 10px;
  padding-right: 30px;
  margin-left: 18px;
}

.logo:hover {
  filter: saturate(280%);
}

.nav-nm-text {
  font-size: 18px;
  margin-left: 4px;
  letter-spacing: 0px;
  margin-top: -1px;
}

.nav-nm {
  margin-top: 2px;
  margin-left: 1px;
  border: none;
  display: flex;
  justify-content: center;
  border-radius: 8px;
  font-weight: 600;
  font-family: "Poppins", Helvetica, Arial, sans-serif;
  text-align: start;
  line-height: normal;
  font-size: 18px;
  align-items: center;
}
.fa-gray {
  color: #ffffff80;
  font-size: 19px;
}
.ButtonAccount {
  font-weight: inherit;
  width: 140px;
  height: 49px;
  margin-top: -2px;
  margin-right: 22px;
  padding-right: 5px;
  border: none;
  border-radius: 8px;
  font-weight: 600;
  letter-spacing: 0px;
  color: #ffffff;
  font-family: "Poppins", Helvetica, Arial, sans-serif;
  text-align: center;
  line-height: normal;
  font-size: 16px;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  align-items: center;
}
.ButtonAccount:hover {
  background-color: rgba(54, 37, 34, 0.623);
  color: #ffffff;
}

.list-account {
  list-style: none;
}

.dropdown-menu {
  position: absolute;
  background: rgba(34, 13, 11, 1);
  width: 320px;
  padding: 12px;
  margin-top: 17px;
  margin-left: -50%;
}

.dropdown-myitem {
  font-weight: inherit;
  width: 100%;
  height: 50px;
  padding-top: 14px;
  border: none;
  border-radius: 8px;
  background: none;
  font-weight: bold;
  color: #ffffff;
  font-family: "Poppins", Helvetica, Arial, sans-serif;
  line-height: normal;
  font-size: 16px;
  text-overflow: ellipsis;
  white-space: nowrap;
  align-items: center;
}

.dropdown-myitem:hover {
  background-color: rgba(54, 37, 34, 0.623);
  color: #ffffff;
}

.btn-access {
  font-weight: inherit;
  width: 280px;
  height: 50px;
  margin-bottom: 14px;
  margin-left: -15px;
  border: none;
  background-color: #0074e0;
  border-radius: 8px;
  font-weight: bold;
  color: #ffffff;
  font-family: "Poppins", Helvetica, Arial, sans-serif;
  text-align: center;
  line-height: normal;
  font-size: 16px;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  align-items: center;
}

.btn-access::before {
  content: "";
  width: 20px;
  margin-left: 40px;
  height: 20px;
  position: absolute;
  background: rgba(34, 13, 11, 1);
  top: -10px;
  transform: rotate(45deg);
}

.btn-access::after {
  content: "";
  width: 180px;
  height: 100px;
  left: 55px;
  position: absolute;
  background: none;
  top: -65px;
}

.btn-access:hover {
  background-color: #148eff;
}

.access-background:hover {
  background: rgba(34, 13, 11, 1);
}

.dropdown:hover > .dropdown-menu {
  display: block;
  transition-delay: 1s;
}

.nav-nm:hover {
  background-color: rgba(54, 37, 34, 0.623);
}
.nav-nm1:hover {
  background-color: rgba(54, 37, 34, 0.623);
}
.nav-faq:hover {
  background-color: rgba(54, 37, 34, 0.623);
}

.nav-faq {
  font-weight: inherit;
  width: 221px;
  height: 50px;
  border: none;
  display: flex;
  justify-content: start;
  border-radius: 8px;
  font-weight: bold;
  font-family: "Poppins", Helvetica, Arial, sans-serif;
  text-align: start;
  line-height: normal;
  font-size: 18px;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  align-items: center;
}
</style>
