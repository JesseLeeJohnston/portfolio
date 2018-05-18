<template>
  <section class="container">
    <h1 class="title">HELLOW WORLD</h1>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style lang="scss">
@import "../assets/main.scss";
.title {
  color: $primary;
}
</style>
