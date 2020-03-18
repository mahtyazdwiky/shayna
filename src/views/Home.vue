<template>
  <div class="home">
    <HeaderShayna />
    <HeroCarousel />
    <ProductCarousel />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroCarousel from "@/components/HeroCarousel.vue";
import ProductCarousel from "@/components/ProductCarousel.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "Home",
  components: {
    HeaderShayna,
    HeroCarousel,
    ProductCarousel,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
};
</script>
