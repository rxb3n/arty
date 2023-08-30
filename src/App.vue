<template>
<NavView/>
<HeroView/>
<AboutView/>
<PortfolioView/>
<ServiceView/>
<CtaView/>
<FooterView/>
</template>

<script>
import NavView from './components/NavView.vue'
import HeroView from './components/HeroView.vue'
import AboutView from './components/AboutView.vue'
import PortfolioView from './components/PortfolioView.vue'
import ServiceView from './components/ServiceView.vue'
import CtaView from './components/CtaView.vue'
import FooterView from './components/FooterView.vue'

export default {
  name: 'App',
  components: {
    NavView,
    HeroView,
    AboutView,
    PortfolioView,
    ServiceView,
    CtaView,
    FooterView,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Archivo:wght@100;400;700&family=Unbounded:wght@400;700&display=swap');

:root {
  --background-color: #FFE8D6;
  --color-secondary: #FFD9BD;
  --btn-color:#A5A58D;
  --font-primary:'Archivo', sans-serif;
  --font-secondary:'Unbounded', sans-serif;
}

body {
  margin: 0;
  padding: 0;
  overflow-x: hidden;
  background-color: var(--background-color);
}

h1, h2, h3, h4, h5, h6, p {
  margin: 0;
  padding: 0;
}


</style>
