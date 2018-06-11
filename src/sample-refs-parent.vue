<template>
  <section>
    <sample-refs ref="sample"></sample-refs>
  </section>
</template>

<script>
import sampleRefs from './sample-refs.vue'

export default {
  data () {
    return {
    }
  },
  mounted () {
    const sampleRef = this.$refs.sample
    console.log(sampleRef.$el)
    const h3 = sampleRef.$el.firstChild
    console.log(h3)
  },
  components: {
    'sample-refs': sampleRefs
  }
}
</script>

<style scoped>
section {
  border: 1px solid #ccc;
}
</style>
