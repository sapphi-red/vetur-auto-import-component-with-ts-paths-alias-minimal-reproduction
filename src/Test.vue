<template>
  <div>
    {{ foo }}
    <test-a />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import * as _ from 'lodash'
import TestA from '/@src/TestA.vue'

export default defineComponent({
  components: { TestA },
  props: ['foo', 'bar']
})
</script>
