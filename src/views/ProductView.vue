<template>
  Product Id is {{$route.params.productId}}

  <router-link :to="`/products/${$route.params.productId}/comments`" >Product's Comment</router-link>
  <router-view></router-view>
</template>