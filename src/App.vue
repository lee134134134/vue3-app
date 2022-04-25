<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import { ref } from "vue";
const count = ref<number>(0);
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <!--  <img alt="Vue logo" src="./assets/logo.png" />-->
  <p>{{ count }}</p>
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>

<style>
body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
