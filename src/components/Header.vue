<script setup>
import MenuComponent from "@/components/Menu/Menu.vue"

const props = defineProps(['image']);


</script>

<template>
    <div class="logo">
        <img 
        :src="props.image"
         alt= "flower">
    </div>
    <MenuComponent ></MenuComponent>
    
    <nav>
        
        
    </nav>
</template>