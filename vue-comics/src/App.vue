<script>
import footerVue from './components/footer.vue'
import headerVue from './components/header.vue'
import mainVue from './components/main.vue'
import cardVue from './components/card.vue'

export default {
  name: 'App',
  components: {
    headerVue,
    mainVue,
    footerVue,
  }
}
</script>

<template>
  <div class="">
    <headerVue />
    <mainVue />
    <footerVue />
  </div>
</template>

<style lang="scss">
  @use './scss/main.scss'
</style>