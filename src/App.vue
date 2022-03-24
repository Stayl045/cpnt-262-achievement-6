<template>
  <section>
    <BaseHeader />
    <h3>{{ pageNavigation }}</h3>
    <ListComponent />
    <BaseBodySection>
      <h1>Hello from Slot</h1>
    </BaseBodySection>
    <TheBaseFooter :title="'&copy; Stephan Taylor, 2022'" />
  </section>
</template>

// imports
<script setup>
  import { computed } from "vue";
  import BaseHeader from "./components/layout/BaseHeader.vue";
  import TheBaseFooter from "./components/layout/TheBaseFooter.vue";
  import ListComponent from "./components/ListComponent.vue";
  import BaseBodySection from "./components/layout/BaseBodySection.vue";

  const pageNavigation =
    "This is a test for using moustache syntax...this does not look great in the slightest";
</script>
