<template>
  <div class="hello-world">
    <h1 class="text-2xl font-bold">Hello World!</h1>
    <p class="mt-4">Welcome to your Vue.js app with TypeScript and Tailwind CSS.</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HelloWorld',
});
</script>

<style scoped>
.hello-world {
  text-align: center;
}
</style>