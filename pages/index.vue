<template>
  <div>
    <h1>Hello World</h1>
    <button @click="bam">Trigger Error</button>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
  methods: {
    bam() {
      throw new Error('BAM!')
    }
  }
})
</script>
