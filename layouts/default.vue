<template>
  <div>
    <!-- Pageloader -->
    <div class="pageloader"></div>
    <!-- <div class="infraloader is-active"></div> -->
    <navbar/>
    <nuxt/>
  </div>
</template>

<script>
import Navbar from '~/components/partials/Navbar.vue'

export default {
  components: {
    Navbar
  }
}

</script>

<style>
</style>
