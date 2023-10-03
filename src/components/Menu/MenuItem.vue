<script setup>
const props = defineProps (["title"]);
</script>

<template>
 <a href="#">{{ props.title }}</a>
</template>

<style scoped>
a{
    margin: 100px 15px;
    padding: 10px 15px;
    background-color: rgb(100, 100, 43);
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    border-radius: 10px;
    color: black;
}


</style>