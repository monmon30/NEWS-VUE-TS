<template>
  <div class="home">
    <HelloWorld msg="Welcome to Mon Your Vue.js + TypeScript App" />
  </div>
</template>

<script setup lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue";
defineComponent({
  name: "Home",
});
</script>
