<template>
  <div class="parent">
    <div
      v-if="
        $route.params.category == 'electronics' &&
          $route.params.product_name == 'ac'
      "
    >
      <h5>now select any brand for ac</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/walton`
        "
        >walton
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/lg`
        "
        >lg
      </NuxtLink>
      <span>|</span>
    </div>

    <div
      v-if="
        $route.params.category == 'electronics' &&
          $route.params.product_name == 'tv'
      "
    >
      <h5>now select any brand for tv</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/lg`
        "
        >lg
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/walton`
        "
        >walton
      </NuxtLink>
      <span>|</span>
    </div>

    <div
      v-if="
        $route.params.category == 'cloth' &&
          $route.params.product_name == 'shirt'
      "
    >
      <h5>now select any brand for shirt</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/puma`
        "
        >puma
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/cats_eye`
        "
        >cats eye
      </NuxtLink>
      <span>|</span>
    </div>

    <div
      v-if="
        $route.params.category == 'cloth' &&
          $route.params.product_name == 'pant'
      "
    >
      <h5>now select any brand for pant</h5>

      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/cats_eye`
        "
        >cats eye
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/puma`
        "
        >puma
      </NuxtLink>
      <span>|</span>
    </div>
    <nuxt-child></nuxt-child>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
