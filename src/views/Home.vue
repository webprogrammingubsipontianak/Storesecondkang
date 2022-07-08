<template>
  <div class="home">
    <HeaderSecondkang />
    <HeroSecondkang />
    <ProductSecondkang />
    <InstagramSecondkang />
    <PartnerSecondkang />
    <FooterSecondkang />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderSecondkang from "@/components/HeaderSecondkang.vue";
import HeroSecondkang from "@/components/HeroSecondkang.vue";
import ProductSecondkang from "@/components/ProductSecondkang.vue";
import InstagramSecondkang from "@/components/InstagramSecondkang.vue";
import PartnerSecondkang from "@/components/PartnerSecondkang.vue";
import FooterSecondkang from "@/components/FooterSecondkang.vue";

export default {
  name: "home",
  components: {
    HeaderSecondkang,
    HeroSecondkang,
    ProductSecondkang,
    InstagramSecondkang,
    PartnerSecondkang,
    FooterSecondkang,
  },
};
</script>
