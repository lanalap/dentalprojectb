<template>
  <div>
    <home />
    <infosection />
  </div>
</template>

<script>
import carousel from "./components/Carousel";
import info from "./components/Info";

export default {
  name: "Lexicon-Dental-Clinic",
  components: {
    home: carousel,
    infosection: info,
  },
};
</script>

<style>
</style>
