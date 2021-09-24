<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script setup lang="ts">
import { defineComponent, defineProps, PropType } from "vue";

defineComponent({
  name: "HelloWorld",
});

defineProps({
  msg: {
    type: String as PropType<string>,
  },
});
</script>
