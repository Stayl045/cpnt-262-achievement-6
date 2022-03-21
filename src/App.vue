<template>
  <div>
    <TheHeader :title="pageHeader" :description="pageDescription" />
    <main>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae vitae
        perferendis laudantium cum, quidem non. At sequi deleniti, nam rem
        minima numquam beatae iure voluptates.
      </p>
    </main>
  </div>
  <TheBodySection>
    <template #body-header>
      <p>
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Modi aut id
        deleniti ea nostrum quam nihil ad possimus porro, fugit itaque,
        perferendis ullam sint cum.
      </p>
    </template>
  </TheBodySection>

  <TheBodySection>
    <template #body-header>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente libero
        excepturi, dicta, deserunt ab ducimus reprehenderit distinctio id ipsa
        vel aut dolore sed quibusdam minima?
      </p>
    </template>
  </TheBodySection>

  <TheFooter />
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

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
