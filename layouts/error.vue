<template>
  <div>
    <div>
        <h1>
          {{ error.statusCode }}
        </h1>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'Error',
  props: {
    error: {
      type: Object,
      required: true,
    },
  },
})
</script>
