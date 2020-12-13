<template>
  <div class="home">
    <header-shayna></header-shayna>
    <hero-shayna></hero-shayna>
    <women-shayna></women-shayna>
    <insta-shayna></insta-shayna>
    <partner-shayna></partner-shayna>
    <footer-shayna></footer-shayna>
  </div>
</template>

<script>
import FooterShayna from '../components/FooterShayna.vue'

import HeaderShayna from '../components/HeaderShayna.vue'
import HeroShayna from '../components/HeroShayna.vue'
import InstaShayna from '../components/InstaShayna.vue'
import PartnerShayna from '../components/PartnerShayna.vue'
import WomenShayna from '../components/WomenShayna.vue'
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
