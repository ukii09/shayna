<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBannerShayna />
    <GalleryShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src

import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import WomenBannerShayna from '@/components/WomenBannerShayna.vue'
import GalleryShayna from '@/components/GalleryShayna.vue'
import PartnerShayna from '@/components/PartnerShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'


export default {
  name: 'home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBannerShayna,
    GalleryShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
