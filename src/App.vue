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
@import "./assets/css/reset.css"; 
#app {
  font-family: 'Lato', 'Noto Sans JP', 'ヒラギノ角ゴ ProN', 'Hiragino Kaku Gothic ProN', 'メイリオ', Meiryo, 'ＭＳ Ｐゴシック', 'MS PGothic', sans-serif;
}
</style>
