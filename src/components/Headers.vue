<template>
  <div class="okok ml-3 mr-3 d-flex justify-content-center">
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
          <button class="ButtonBlizzHeader2 pt-1" type="submit">
            Suscribirse
          </button>
          <button class="ButtonBlizzHeader1 pt-1" type="submit">
            Comprar mejoras
          </button>
        </form>
      </div>
    </nav>
  </div>
</template>

<script>
import MiniLogoCataclysm from './MiniLogoCataclysm.vue'

export default {
  components:{MiniLogoCataclysm},
  name: "Headers",
};
</script>

<style scoped>
.BlizzNavbar {
  margin-top: -32px;
  background-color: rgba(34, 13, 11, 0.8);
  width: 2500px;
  height: 70px;
  border-radius: 8px;
  z-index: 2;
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

.ButtonBlizzHeader1 {
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
  text-overflow: ellipsis;
  white-space: nowrap;
  align-items: center;
}

.ButtonBlizzHeader2 {
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

.ButtonBlizzHeader2:hover {
  background-color: #a01d00;
}

.ButtonBlizzHeader1:hover {
  background-color: #151515;
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

.btn-access:hover {
  background-color: #148eff;
}

.access-background:hover {
  background: rgba(34, 13, 11, 1);
}

/* .dropdown:hover>.dropdown-menu {
  display: block;
  
}

.dropdown>.dropdown-toggle:active {
    pointer-events: none;
    
}  */

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
