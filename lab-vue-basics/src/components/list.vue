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
            {{ book.title }}
        </li>
    </ul>
</template>


<style></style>