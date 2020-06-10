<template>
  <div id="app" class="applicaitonPage">
    <!-- <Users /> -->
    <Header />
    <WhatOffer />
    <WhatIdea />
    <WhatPortfolio />
    <WhatTestimonial />
    <WhatTechnology />
    <MeetProfessinals />
    <Footer />
  </div>
</template>

<script>
// import Users from './components/Users.vue'
import Header from './components/Header.vue'
import WhatOffer from './components/WhatOffer.vue'
import WhatIdea from './components/WhatIdea.vue'
import WhatPortfolio from './components/WhatPortfolio.vue'
import WhatTestimonial from './components/WhatTestimonial.vue'
import WhatTechnology from './components/WhatTechnology.vue'
import MeetProfessinals from './components/MeetProfessinals.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    // Users,
    Header,
    WhatOffer,
    WhatIdea,
    WhatPortfolio,
    WhatTestimonial,
    WhatTechnology,
    MeetProfessinals,
    Footer
  }
}
</script>

<style lang="scss">
  @import "@/assets/scss/app.scss";
</style>