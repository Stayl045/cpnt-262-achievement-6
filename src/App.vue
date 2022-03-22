<template>
  <section>
    <BaseHeader />
    <h3>{{ pageNavigation }}</h3>

    <ListComponent />

    <BaseBodySection>
      <template #body-header />
    </BaseBodySection>
    <BaseFooter />
  </section>
</template>

// imports //
<script setup>
  import { computed } from "vue";
  import BaseHeader from "./components/layout/BaseHeader.vue";
  import BaseFooter from "./components/layout/BaseFooter.vue";
  import ListComponent from "./components/ListComponent.vue";
  import BaseBodySection from "./components/layout/BaseBodySection.vue";
  import TheBodyHeader from "./components/ui/TheBodyHeader.vue";

  const pageNavigation = "Home";
  const pageDescription = "This is the landing page";

  // Computed Example using .map
  // const numberArray = [1, 2, 3, 4, 5];
  // return numberArray.map((num) => num * 5);
</script>
