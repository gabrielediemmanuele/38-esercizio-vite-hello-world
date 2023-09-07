<!--TODO CODICE JS -->
<script>
export default {
  data() {
    return {
      image:
        "../assets/img/1000x563_cmsv2_26c9e590-9491-522c-8def-11ce8b71d3f8-6589278.jpg",
    };
  },
  //! Path dinamico Immagini
  methods: {
    buildImagePath(path) {
      const imageUrl = new URL(path, import.meta.url);
      console.log(imageUrl);

      return imageUrl.href;
    },
  },
};
</script>

<!--TODO HTML -->
<template>
  <img :src="buildImagePath(image)" :alt="image" />
</template>

<!--TODO CSS -->
<style></style>
