<template>
  <div>
    <h1>Hello from ExampleComponent!</h1>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'ExampleComponent',
});
</script>

<style scoped>
h1 {
  color: blue;
}
</style>