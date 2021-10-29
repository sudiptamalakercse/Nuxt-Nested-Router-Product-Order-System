<template>
  <div class="parent">
    <h5>selected category type is {{ $route.params.category }}</h5>
    <h5>now select any product</h5>
    <div v-if="$route.params.category == 'electronics'">
      <span>|</span>
      <NuxtLink :to="`/products/${$route.params.category}/ac`">ac</NuxtLink>
      <span>|</span>
      <NuxtLink :to="`/products/${$route.params.category}/tv`">tv</NuxtLink>
      <span>|</span>
    </div>
    <div v-if="$route.params.category == 'cloth'">
      <span>|</span>
      <NuxtLink :to="`/products/${$route.params.category}/pant`">pant</NuxtLink>
      <span>|</span>
      <NuxtLink :to="`/products/${$route.params.category}/shirt`"
        >shirt</NuxtLink
      >
      <span>|</span>
    </div>
    <nuxt-child></nuxt-child>
  </div>
</template>
