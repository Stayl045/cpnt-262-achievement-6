<template>
  <header>
    <h2>{{ props.title }}</h2>
    <p>{{ props.description }}</p>
  </header>
</template>

<script setup>
  import { defineProps } from "vue";
  const props = defineProps({
    title: {
      type: String,
      default: "Default Text",
    },
    description: {
      type: String,
      default: "a simple description",
    },
  });
</script>
