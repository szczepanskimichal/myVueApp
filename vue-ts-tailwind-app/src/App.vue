<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App with TypeScript and Tailwind CSS!" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from './components/HelloWorld.vue';

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  }
});
</script>

<style>
@import './assets/styles.css'; /* Assuming you have a styles.css for Tailwind */
</style>