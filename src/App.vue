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
    <TheFooter />
  </div>
</template>

<script setup>
  import TheHeader from "./components/TheHeader.vue";
  import TheFooter from "./components/TheFooter.vue";
  const pageHeader = "Home Page";
  const pageDescription = "This is the landing page";
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
