<template>
  <div><TextInput /></div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue'
  import TextInput from '/@/components/form/TextInput.vue'

  export default defineComponent({
    name: 'App',
    components: {
      TextInput,
    },
  })
</script>
