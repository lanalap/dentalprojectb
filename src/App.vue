<template>
  <div>
    <AppTopNavbar/>
    <AppNavbar/>
    <home />
  </div>
</template>

<script>
import carousel from "./components/Carousel";
import topnavbar from './components/TopNavbar'
import navbar from './components/Navbar'

export default {
  name: "Lexicon-Dental-Clinic",
  components: {
    AppTopNavbar: topnavbar,
    AppNavbar: navbar,
    home: carousel,
  },
};
</script>

<style>
</style>
