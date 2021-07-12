<template>
  <div >
    <appOurService />
    <appFooter />
   
  </div>
</template>

<script>
import OurService from './components/ourServiceSection/OurService.vue'
import footer from './components/footerSection/footer.vue'

export default {
  name : 'App',
  components : {
    appOurService : OurService,
    appFooter: footer
  }
}
</script>

<style>
html, body{
    margin: 0;
    font-family: 'Roboto', sans-serif;
    line-height: 1.5;
    background-color:#FFFFFF;
 
}

</style>
