<template>
  <div class="home">
    <HeaderOlshop />
    <HeroOlshop />
    <BannerOlshop />    
    <InstaOlshop />
    <PartnerOlshop />
    <FooterOlshop />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderOlshop from '@/components/HeaderOlshop.vue'
import HeroOlshop from '@/components/HeroOlshop.vue'
import BannerOlshop from '@/components/BannerOlshop.vue'
import InstaOlshop from '@/components/InstaOlshop.vue'
import PartnerOlshop from '@/components/PartnerOlshop.vue'
import FooterOlshop from '@/components/FooterOlshop.vue'


export default {
  name: 'Home',
  components: {
    HeaderOlshop,
    HeroOlshop,
    BannerOlshop,
    InstaOlshop,
    PartnerOlshop,
    FooterOlshop
  }
}
</script>
