<script setup>
import {ref} from 'vue';

const library = ref([
    { title: "nana", author: "zola", description: "classic" },
    { title: "1984", author: "orwell", description: "anticipation novel" },
    { title: "ravage", author: "barjavel", description: "science fiction" }
]);

</script>


<template>
    <ul>
        <li v-for="book in library">
            Title : {{ book.title }}, Author :  {{ book.author }}, Description : {{ book.description }}
        </li>
    </ul>
</template>


<style>

</style>