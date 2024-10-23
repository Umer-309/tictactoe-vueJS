<template>
  <div class="tic-tac-toe">
    <composition-tictac></composition-tictac>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import CompositionTictac from './components/compositionTictac.vue'

export default defineComponent({
  components: {
    CompositionTictac,
  },
})
</script>
