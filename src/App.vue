<template>
  <h1>Slot HMR Bug Reproductions</h1>
  <SimpleSlot>
    Outside Slot
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
