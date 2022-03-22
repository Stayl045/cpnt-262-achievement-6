<template>
  <header>
    <h2>{{ props.title }}</h2>
  </header>
</template>

<script setup>
  const props = defineProps({
    title: {
      type: String,
      default: "The main page",
    },
  });
</script>
