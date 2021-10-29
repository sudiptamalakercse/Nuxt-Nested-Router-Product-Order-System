<template>
  <div class="parent">
    <div
      v-if="
        ($route.params.category == 'electronics' ||
          $route.params.category == 'cloth') &&
          ($route.params.product_name == 'ac' ||
            $route.params.product_name == 'tv' ||
            $route.params.product_name == 'shirt' ||
            $route.params.product_name == 'pant') &&
          ($route.params.brand == 'lg' ||
            $route.params.brand == 'walton' ||
            $route.params.brand == 'puma' ||
            $route.params.brand == 'cats_eye') &&
          $route.params.product_unique_id != ''
      "
    >
      <p class="p-2">
        <span class="span">selected product description </span> <br />
        product category: {{ $route.params.category }} <br />
        product name: {{ $route.params.product_name }}<br />
        product brand: {{ $route.params.brand }}<br />
        product unique id: {{ $route.params.product_unique_id }} <br />
        <span v-if="$route.params.category == 'cloth'"
          >product price: 1500 tk <br
        /></span>
        <span v-else>product price: 50000 tk <br /></span>
        <input
          class="mt-2"
          type="button"
          value="place order "
          @click.prevent="onSubmmit"
        />
      </p>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    onSubmmit() {
      alert("order is successfully confirmed!");
      this.$router.replace("/");
    }
  }
};
</script>

<style></style>
