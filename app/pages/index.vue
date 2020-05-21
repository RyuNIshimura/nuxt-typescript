<template lang="pug">
  div.container
    div
      logo
      h1.title
        nuxt-typescript
      h2.subtitle
        My tiptop Nuxt.js project
      div.links
        a.button--green(href="https://nuxtjs.org/" target="_blank")
          | Documentation
        a.button--grey(href="https://github.com/nuxt/nuxt.js" target="_blank")
          | GitHub
</template>

<script lang="ts">
import Vue from "vue";
import Logo from "~/components/atoms/Logo.vue";

export default Vue.extend({
  components: {
    Logo,
  },
});
</script>
