<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <BannerSlide />
    <GaleryShayna />
    <LogoShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import BannerSlide from "@/components/BannerSlide.vue";
import GaleryShayna from "@/components/GaleryShayna.vue";
import LogoShayna from "@/components/LogoShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";


export default {
  name: "home",
  components: {
    HeaderShayna,
    HeroShayna,
    BannerSlide,
    GaleryShayna,
    LogoShayna,
    FooterShayna

  }
}
</script>
