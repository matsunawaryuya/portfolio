<template lang="pug">
.index-page
  Header
  About
  Skill
  Works
  Contact
  Footer
</template>

<script>
import { defineComponent } from "@vue/composition-api";
import Header from '../components/Header';
import About from '../components/About';
import Skill from '../components/Skill';
import Works from '../components/Works';
import Contact from '../components/Contact';
import Footer from '../components/Footer';

export default defineComponent({
  name: 'Index',
  components: {
    Header,
    About,
    Skill,
    Works,
    Contact,
    Footer
  }
});
</script>
