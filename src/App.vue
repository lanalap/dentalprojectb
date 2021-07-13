<template>
  <div>
    <AppTopNavbar />
    <AppNavbar />
    <home />
    <infosection />
    <appOurService />
    <appFooter />
  </div>
</template>

<script>
import carousel from "./components/Carousel";
import info from "./components/Info";
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
    infosection: info,
    appOurService: OurService,
    appFooter: footer
  },
};
</script>

<style>
</style>
