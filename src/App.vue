<script setup>
import HeaderComponent from "@/components/Header.vue";
import FooterComponent from "@/components/Footer.vue";

const headerImage= "https://images.unsplash.com/photo-1628076674561-6e9a0b56f2c3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=200&q=80";
</script>

<template>
  <HeaderComponent :image="headerImage" ></HeaderComponent>  
  <main>
    <h1>VUE PROJECT :S</h1>
  </main>
  <FooterComponent text="VISIT US AGAIN :D"></FooterComponent>
</template>


