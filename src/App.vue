<template>
  <section>
    <TheHeader />
    <main>
      <p class="text-xl">
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae vitae
        perferendis laudantium cum, quidem non. At sequi deleniti, nam rem
        minima numquam beatae iure voluptates.
      </p>
    </main>

    <TheBodySection>
      <template #body-header />
    </TheBodySection>
    <TheFooter />
  </section>
</template>

// imports //
<script setup>
  import { computed } from "vue";
  import TheHeader from "./components/TheHeader.vue";
  import TheFooter from "./components/TheFooter.vue";
  import TheBodySection from "./components/TheBodySection.vue";
  import TheBodyHeader from "./components/TheBodyHeader.vue";

  const pageHeader = "Home Page";
  const pageDescription = "This is the landing page";

  // Computed Example using .map
  // const numberArray = [1, 2, 3, 4, 5];
  // return numberArray.map((num) => num * 5);
</script>
