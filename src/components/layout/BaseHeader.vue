<template class="flex flex-col rounded-sm py-4">
  <header class="grid place-items-center text-center mx-1 bg-slate-500">
    <h2 class="text-black text-3xl md:text-4xl font-medium">
      {{ props.title }}
    </h2>
    <TheNavBar />
    <p>{{ props.description }}</p>

    <!-- Make nav bar component later -->
  </header>
</template>

<script setup>
  import TheNavBar from "../ui/TheNavBar.vue";

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
