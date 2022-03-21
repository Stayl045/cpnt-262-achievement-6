<template>
  <section>
    <!-- <TheBodyHeader /> -->
    <slot name="body-header"></slot>
  </section>
</template>

<script setup>
  import TheBodyHeader from "./TheBodyHeader";
  const props = defineProps({
    title: {
      type: String,
    },
  });

  // Vue Conditionals from Class //
  //   const props = defineProps({
  //     title: {
  //       type: String,
  //     },
  //   });
  //
</script>
