<template>
  <div>
    <div class="pageloader"></div>
    <div class="infraloader is-active"></div>
    <navbar-main-menu/>
    <nuxt/>
  </div>
</template>

<script>
import NavbarMainMenu from '~/components/partials/NavbarMainMenu.vue'

export default {
  components: {
    NavbarMainMenu
  }
}

</script>

<style>
</style>
