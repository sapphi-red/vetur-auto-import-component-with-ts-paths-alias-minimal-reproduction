<template>
  <div>
    {{ foo }}
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: ['foo', 'bar']
})
</script>
