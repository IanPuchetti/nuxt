<template>
  <section class="container">
    <div>
      <h1 class="title">
        Help
      </h1>
      <h2 class="subtitle">
        Some text helping {{name}}
      </h2>
      <nuxt-link to="/" class="button--grey">Back</nuxt-link>
    </div>
  </section>
</template>

<script>

export default {
  data () {
    return {
      name: this.$route.query.name
    }
  },
  created () {
  }
}
</script>
