<template>
  <div class="parent">
    <h5>products</h5>
    <span>|</span>
    <NuxtLink to="/products/electronics">electronics</NuxtLink>
    <span>|</span>
    <NuxtLink to="/products/cloth">cloth</NuxtLink>
    <span>|</span>
    <nuxt-child></nuxt-child>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
