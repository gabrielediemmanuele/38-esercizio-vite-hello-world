<!--TODO CODICE JS -->
<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {
      title: "App Vue",
    };
  },
  components: { AppTitle, AppHero },
};
</script>

<!--TODO HTML -->
<template>
  <div class="container">
    <AppTitle class="app-title"></AppTitle>
    <AppHero class="image"></AppHero>
  </div>
</template>

<!--TODO CSS -->
<style></style>
