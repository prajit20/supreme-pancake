<template>
  <v-app>
   {{Value}}
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';




export default defineComponent({
  name: 'App',
  components: {

  },
  setup() {
    const Value = 'Hello';
    console.log(Value)
    return {
      Value
    };
  }
});
</script>
