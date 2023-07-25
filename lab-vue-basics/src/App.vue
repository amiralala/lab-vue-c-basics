<script setup>
import Nav from './components/Nav.vue';
import Footer from './components/Footer.vue';
import { ref, computed } from 'vue';
import Conditional from './components/Conditional.vue';

const myText = ref("May it work");

const reverseText = computed(() => {
  let reversed = "";
  const l = myText.value.length;
  for (let i = 0; i <= l; i++){
    reversed += myText.value.charAt(l - i);
  }
  return reversed;
})
</script>

<template>
  <Nav></Nav>
  <p>
    Formulation
    2+2= {{ 2 + 2 }}
  </p>
  <p>reversed string : {{ reverseText }}</p>
  <Conditional></Conditional>
  <Footer></Footer>
</template>

<style></style>