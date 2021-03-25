<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <BannerShayna />
    <GalleryShayna />
    <LogoPartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
  // @ is an alias to /src
  import HeaderShayna from '@/components/HeaderShayna.vue';
  import HeroShayna from '@/components/HeroShayna.vue';
  import BannerShayna from '@/components/BannerShayna.vue';
  import GalleryShayna from '@/components/GalleryShayna.vue';
  import LogoPartnerShayna from '@/components/LogoPartnerShayna.vue';
  import FooterShayna from '@/components/FooterShayna.vue';

  export default {
    name: 'Home',
    components: {
      HeaderShayna,
      HeroShayna,
      BannerShayna,
      GalleryShayna,
      LogoPartnerShayna,
      FooterShayna
    }
  }
</script>