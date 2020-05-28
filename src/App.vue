<template>
  <h1>Slot HMR Bug Reproduction</h1>
  <SimpleSlot>
    Outside Slot
    <SimpleSlot>
      Inside Slot
    </SimpleSlot>
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
