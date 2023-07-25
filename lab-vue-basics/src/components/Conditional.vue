<script setup>
import { ref } from 'vue';
let conditionValue=ref(false);
</script>



<template>
 <input type="checkbox" v-model="conditionValue" >   
 <label for="checkbox">{{ conditionValue }}</label>
 <p v-if="conditionValue===true">condition is true, i'm displayed!</p>
</template>



<style>

</style>