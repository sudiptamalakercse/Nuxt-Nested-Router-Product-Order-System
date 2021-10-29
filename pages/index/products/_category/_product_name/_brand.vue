<template>
  <div class="parent">
    <div
      v-if="
        $route.params.category == 'electronics' &&
          $route.params.product_name == 'ac' &&
          $route.params.brand == 'lg'
      "
    >
      <h5>now place order any lg ac</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/ac-lg-1`
        "
        >ac-lg-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/ac-lg-2`
        "
        >ac-lg-2
      </NuxtLink>
      <span>|</span>
    </div>
    <div
      v-if="
        $route.params.category == 'electronics' &&
          $route.params.product_name == 'tv' &&
          $route.params.brand == 'lg'
      "
    >
      <h5>now place order any lg tv</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/tv-lg-1`
        "
        >tv-lg-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/tv-lg-2`
        "
        >tv-lg-2
      </NuxtLink>
      <span>|</span>
    </div>
    <div
      v-if="
        $route.params.category == 'electronics' &&
          $route.params.product_name == 'ac' &&
          $route.params.brand == 'walton'
      "
    >
      <h5>now place order any walton ac</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/ac-walton-1`
        "
        >ac-walton-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/ac-walton-2`
        "
        >ac-walton-2
      </NuxtLink>
      <span>|</span>
    </div>
    <div
      v-if="
        $route.params.category == 'electronics' &&
          $route.params.product_name == 'tv' &&
          $route.params.brand == 'walton'
      "
    >
      <h5>now place order any walton tv</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/tv-walton-1`
        "
        >tv-walton-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/tv-walton-2`
        "
        >tv-walton-2
      </NuxtLink>
      <span>|</span>
    </div>
    <div
      v-if="
        $route.params.category == 'cloth' &&
          $route.params.product_name == 'shirt' &&
          $route.params.brand == 'puma'
      "
    >
      <h5>now place order any puma shirt</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/shirt-puma-1`
        "
        >shirt-puma-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/shirt-puma-2`
        "
        >shirt-puma-2
      </NuxtLink>
      <span>|</span>
    </div>
    <div
      v-if="
        $route.params.category == 'cloth' &&
          $route.params.product_name == 'pant' &&
          $route.params.brand == 'puma'
      "
    >
      <h5>now place order any puma pant</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/pant-puma-1`
        "
        >pant-puma-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/pant-puma-2`
        "
        >pant-puma-2
      </NuxtLink>
      <span>|</span>
    </div>
    <div
      v-if="
        $route.params.category == 'cloth' &&
          $route.params.product_name == 'shirt' &&
          $route.params.brand == 'cats_eye'
      "
    >
      <h5>now place order any cats_eye shirt</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/shirt-cats_eye-1`
        "
        >shirt-cats_eye-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/shirt-cats_eye-2`
        "
        >shirt-cats_eye-2
      </NuxtLink>
      <span>|</span>
    </div>
    <div
      v-if="
        $route.params.category == 'cloth' &&
          $route.params.product_name == 'pant' &&
          $route.params.brand == 'cats_eye'
      "
    >
      <h5>now place order any cats_eye pant</h5>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/pant-cats_eye-1`
        "
        >pant-cats_eye-1
      </NuxtLink>
      <span>|</span>
      <NuxtLink
        :to="
          `/products/${$route.params.category}/${$route.params.product_name}/${$route.params.brand}/pant-cats_eye-2`
        "
        >pant-cats_eye-2
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
