<template lang="pug">
.index-page
  Header
</template>

<script>
import { defineComponent } from "@vue/composition-api";
import Header from '../components/Header';

export default defineComponent({
  name: 'Index',
  components: {
    Header
  }
});
</script>
