<template>
  <section>
    <!-- <TheBodyHeader /> -->
    <slot name="body-header" />
    <h1>This is the body header</h1>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates
      asperiores culpa consectetur voluptatibus animi deleniti! Enim impedit est
      voluptas ex nesciunt voluptates quia, deleniti alias.
    </p>
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
