<template class="flex flex-col rounded-sm py-4">
  <header class="grid place-items-center text-center mx-1">
    <h2 class="text-black text-3xl md:text-4xl font-medium">
      {{ props.title }}
    </h2>
    <p>{{ props.description }}</p>
  </header>
</template>

<script setup>
  // const props = defineProps({
  //   title: {
  //     type: String,
  //     default: "a simple description",
  //     description: String,
  //     default: "More stuff",
  //   },
  // });
  import { defineProps } from "vue";
  const props = defineProps({
    title: {
      type: String,
      default: "Vue Components",
    },
    description: {
      type: String,
      default: "a simple description",
    },
  });
</script>
