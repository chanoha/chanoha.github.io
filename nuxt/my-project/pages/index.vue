<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        nuxt_project
      </h1>
      <h2 class="subtitle">
        nuxt no project
        test
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
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

<style lang="scss" scoped>
@import "../assets/scss/variable.scss";
</style>