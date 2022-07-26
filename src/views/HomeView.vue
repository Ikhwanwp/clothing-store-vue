<template>
  <div class="home">
    <HeaderStore />
    <HeroStore />
    <ProductStore />
    <SosmedStore />
    <PartnerStore />
    <FooterStore />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderStore from "@/components/HeaderStore.vue";
import FooterStore from "@/components/FooterStore.vue";
import HeroStore from "@/components/HeroStore.vue";
import ProductStore from "@/components/ProductStore.vue";
import SosmedStore from "../components/SosmedStore.vue";
import PartnerStore from "../components/PartnerStore.vue";

export default {
  name: "HomeView",
  components: {
    HeaderStore,
    HeroStore,
    FooterStore,
    ProductStore,
    SosmedStore,
    PartnerStore,
  },
};
</script>
