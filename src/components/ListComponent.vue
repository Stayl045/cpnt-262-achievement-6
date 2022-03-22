<template>
  <ul>
    <h3 class="grid place-items-center text-center text-2xl text-blue-400">
      List of Animals
    </h3>
    <li
      v-for="item in animals"
      :key="item.id"
      class="place-items-center text-center mx-1 flex flex-col bg-blue-100 rounded-sm py-4"
    >
      {{ item.animal }}
    </li>
  </ul>
</template>

<script setup>
  import { ref } from "vue";
  const animals = ref([
    { animal: "bear" },
    { animal: "wolf" },
    { animal: "moose" },
    { animal: "deer" },
  ]);
</script>
