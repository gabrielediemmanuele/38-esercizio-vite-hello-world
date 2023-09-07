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
    <div class="black-screen">
      <AppHero class="image"></AppHero>
    </div>
  </div>
</template>

<!--TODO CSS -->
<style></style>
