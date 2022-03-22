<script setup>
  import { ref } from "vue";
  const animals = ref([
    { animal: "bear" },
    { animal: "wolf" },
    { animal: "moose" },
    { animal: "deer" },
  ]);
</script>

<template>
  <ul>
    <li v-for="item in animals">
      {{ item.animal }}
    </li>
  </ul>
</template>
