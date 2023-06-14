<template>
  <NavbarSec />
  <HeroSec />
  <CardProduct />
</template>

<script>
import NavbarSec from './components/NavbarSec.vue'
import HeroSec from './components/HeroSec.vue'
import CardProduct from './components/CardProduct.vue'

export default {
  name: 'App',
  components: {
    NavbarSec,
    HeroSec,
    CardProduct
  }
}
</script>

<style>

</style>
