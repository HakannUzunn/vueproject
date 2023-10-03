<script setup>
import MenuComponent from "@/components/Menu/Menu.vue"

const props = defineProps(["text"]);
</script>

<template>
    <footer>
         2023 &copy; Hakan UZUN
         <div>
            <h3>{{ props.text }}</h3>
         </div>
    </footer>
 </template>

 <style scoped>
footer{
    margin : 10px;
    padding: 20px 20px;
    background-color: rgb(25, 82, 67);
    color: black;
}
</style>