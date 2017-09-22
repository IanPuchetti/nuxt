<template>
  <div>
      <navbar/>
      <nuxt/>
      <foot/>
  </div>
</template>

<script>
  import navbar from '../components/navbar.vue'
  import foot from '../components/foot.vue'

  export default {
    components: {
      navbar,
      foot
    }
  }
</script>
