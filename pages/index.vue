<template>
  <div class="container mt-5 parent">
    <h5>top parent</h5>
    <h5>please place an order</h5>
    <span>|</span>
    <NuxtLink to="/products">products</NuxtLink>
    <span>|</span>
    <NuxtLink to="/hello">hello child</NuxtLink>
    <span>|</span>
    <nuxt-child></nuxt-child>
  </div>
</template>

<script>
export default {};
</script>
<style>
.parent {
  text-align: center;
  margin-top: 10px;
  padding: 5px;
  border: 1px solid rgb(102, 146, 35);
}
h5 {
  color: rgb(102, 146, 35);
}
p {
  margin: 0px;
}
.span {
  font-weight: 500;
  color: rgb(102, 146, 35);
  font-size: 21px;
}
a {
  color: black;
}
a:hover {
  color: black;
}
</style>
