<template>
  <div class="product">
    <product-cards />
  </div>
</template>

<script>
import ProductCards from "../components/ProductCards.vue";
export default {
  name: "ProductView",
  components: {
    ProductCards,
  },
};
</script>