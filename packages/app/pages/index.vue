<template>
  <main>
    <Logo />
    <Banner />
  </main>
</template>

<script>
import Banner from "@nuxt-monorepo/vue-shared-components/dist/banner/Banner.common.js"
import "@nuxt-monorepo/vue-shared-components/dist/banner/Banner.css"

export default {
  name: "index.vue",
  components: { Banner },
}
</script>
