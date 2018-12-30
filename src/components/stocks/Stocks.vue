<template>
  <div class="col-lg-12">
    <app-stock v-for="stock in stocks" :stock="stock"></app-stock>
  </div>
</template>

<script>
import Stock from "./Stock.vue";

export default {
  data() {
    return {
      stocks: [
        { id: 1, name: "Apple", price: 101 },
        { id: 2, name: "Tiger", price: 88 },
        { id: 2, name: "Big Bird", price: 110 },
        { id: 4, name: "Twitter", price: 99 }
      ]
    };
  },
  components: {
    appStock: Stock
  }
};
</script>
