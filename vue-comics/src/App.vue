<script>
import footerVue from './components/footer.vue'
import headerVue from './components/header.vue'
import mainVue from './components/main.vue'


export default {
  name: 'App',
  components: {
    headerVue,
    mainVue,
    footerVue
  }
}
</script>

<template>
  <headerVue />
  <mainVue />
  <footerVue />
</template>

<style lang="scss">
  
</style>