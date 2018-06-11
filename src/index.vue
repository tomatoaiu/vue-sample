<template>
  <main>
    <h3>vue ref</h3>
    <sample-refs-parent></sample-refs-parent>
  </main>
</template>

<script>
import sampleRefsParent from './sample-refs-parent.vue'

export default {
  components: {
    'sample-refs-parent': sampleRefsParent
  }
}
</script>

<style scoped>

</style>
