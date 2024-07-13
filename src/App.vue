<template>
  <Banner />
  <Info />
  <characteristics />
  <deathwing />
  <faqComponet />
  <CardGroup />
  <foots />
</template>

<script>

import Banner from './components/Banner.vue'
import Info from './components/Info.vue'
import characteristics from './components/Characteristics.vue'
import deathwing from './components/Deathwing.vue'
import CardGroup from './components/CardGroup.vue'
import foots from './components/Footer.vue'
import faqComponet from './components/FaqComponent.vue'

export default {
  name: 'App',
  components: {
    Banner,
    Info,
    characteristics,
    deathwing,
    CardGroup,
    foots,
    faqComponet,


  }
  
}
</script>

<style>

@font-face {
  font-family: "Quadrat Serial";
  src: url(@/assets/quadrat_serial.woff2);
}

@font-face {
  font-family: "Open Sans";
  src: url(@/assets/openSans-600-normal.woff);
}

h1 {
  color: #fff;
  font-family: "Quadrat Serial", serif;
  font-size: 60px;
  font-weight: 400;
}

h2 {
  margin-top: 37px;
  color: #fff;
  font-family: "Quadrat Serial", serif;
  font-size: 48px;
  font-weight: 400;
}

h3 {
  text-align: left;
  color: #ffffff80;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  margin-bottom: 2px;
  padding-bottom: 2px;
  font-size: 18px;
  letter-spacing: 1px;
  font-weight: 600;
  font-family: "Quadrat Serial", serif;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  background: linear-gradient(90deg, #ffa800 0%, #ff8a00 119.41%),
    rgba(255, 255, 255, 0.5);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}
h4 {
  color: #ffffff80;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  margin-bottom: 2px;
  margin-top: 140px;
  padding-bottom: 2px;
  font-size: 28px;
  letter-spacing: 1px;
  font-weight: 600;
  font-family: "Quadrat Serial", serif;
  filter: drop-shadow(4px 2px 4px rgba(0, 0, 0, 0.4));
  background: linear-gradient(90deg, #ffa800 0%, #ff8a00 119.41%),
    rgba(255, 255, 255, 0.5);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

*{
  background: transparent;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background: url('@/assets/Repeating-BG.avif');
  background-size: cover ;
  background-position: center;
  background-attachment: fixed;
  z-index: 1;   
  
  
}


</style>
