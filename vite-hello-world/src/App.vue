<script>
import AppHero from "./components/AppHero.vue";
export default {
  data() {
    return {
      title: "Vite hello world",
    };
  },
  components: { AppHero },
  mounted() {
    console.log("vue funzionante");
  },
};
</script>

<template>
  <h1>{{ title }}</h1>
  <app-hero />
</template>

<style></style>
