<template>
  <div>
    <AppTopNavbar />
    <AppNavbar />
    <home />
    <appOurService />
    <appFooter />
  </div>
</template>

<script>
import carousel from "./components/Carousel";
import topnavbar from "./components/TopNavbar";
import navbar from "./components/Navbar";
import OurService from "./components/ourServiceSection/OurService.vue";
import footer from "./components/footerSection/footer.vue";

export default {
  name: "Lexicon-Dental-Clinic",
  components: {
    AppTopNavbar: topnavbar,
    AppNavbar: navbar,
    home: carousel,
    appOurService: OurService,
    appFooter: footer,
  },
};
</script>

<style>
</style>
