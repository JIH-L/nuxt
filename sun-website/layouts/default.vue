<template lang="pug">
  #page
    HeaderVue
    nuxt
    FooterVue
</template>

<script>
import HeaderVue from '@/components/header/Header.vue';
import FooterVue from '@/components/footer/Footer.vue';

export default {
  components: {
    HeaderVue,
    FooterVue
  }
}
</script>

<style lang="scss">
  
</style>
