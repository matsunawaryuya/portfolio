<template lang="pug">
#app
  index
</template>

<script>
import { defineComponent } from '@vue/composition-api';
import Index from './pages/Index.vue';

export default defineComponent({
  name: 'App',
  components: {
    Index
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
