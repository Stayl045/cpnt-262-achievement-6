<template>
  <footer class="grid place-items-center text-center mx-1">
    <p>{{ props.title }}</p>
  </footer>
</template>

<script setup>
  const props = defineProps({
    title: {
      type: String,
      default: "&copy; Stephan Taylor, 2022",
    },
  });
</script>
