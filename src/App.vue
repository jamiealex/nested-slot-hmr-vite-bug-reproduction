<template>
  <h1>Slot HMR Bug Reproduction</h1>
  <SimpleSlot>
    Slot Content
  </SimpleSlot>
</template>

<script>
import SimpleSlot from './components/SimpleSlot.vue'

export default {
  name: 'App',
  components: {
    SimpleSlot
  }
}
</script>
