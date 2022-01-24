<template>
  <div>
    <Navbar />
    <Promo />
    <Events />
  </div>
</template>

<script>

import Navbar from './components/Navbar.vue';
import Promo from './components/Promo.vue'
import Events from './components/Events.vue';


export default {
  name: 'App',

  components: {
    Navbar,
    Promo,
    Events
  },

  data: () => ({
  }),
};
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Nanum+Gothic:wght@400;700;800&display=swap');
  @import './styles/index.scss';

  * {
    margin: 0;
    padding: 0;
    font-family: 'Nanum Gothic', sans-serif;
  }

  ul, ol {
    list-style: none;
  }

  h1 {
    font-size: $h1-font-size;
  }

  h2 {
    font-size: $h2-font-size;
  }

  h3 {
    font-size: $h3-font-size;
  }

  button {
    font-size: $button-font-size;
    font-weight: $button-font-weight;
  }
</style>