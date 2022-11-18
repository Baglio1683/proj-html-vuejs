<!-- Start script js  -->
<script>
import AppHeaderTop from "./components/AppHeaderTop.vue";
import AppHeaderDown from "./components/AppHeaderDown.vue";
import AppJumbo from "./components/AppJumbo.vue";
import AppContactBanner from "./components/AppContactBanner.vue";
import AppSectionCourses from "./components/AppSectionCourses.vue";
import AppCentralBanner from './components/AppCentralBanner.vue'


export default {

  components : {
    AppHeaderTop, 
    AppHeaderDown,
    AppJumbo,  
    AppContactBanner, 
    AppSectionCourses,
    AppCentralBanner, 
  }, 

  data(){
    return{
    }
  }

}

</script>
<!-- End script js  -->


<!-- Start Template html  -->
<template>

<!-- Start Header -->
<header>

 <AppHeaderTop />
 <AppHeaderDown />

</header>
<!-- End header -->

<!-- Start main  -->
<main>

<AppJumbo />
<AppContactBanner />
<AppSectionCourses />
<AppCentralBanner />

</main>
<!-- End Main  -->

<!-- Start Footer  -->
<footer>
</footer>
<!-- End Footer -->

</template>
<!-- End template Html  -->


<!-- Start style css  -->
<style lang="scss">
@use "./styles/general.scss" as *;
@use "./styles/partials/variables" as *;


header{
  height: 28vh;
  position: fixed;
  width: 100%;
}


main{
  position: absolute;
    top : 10vh;
    z-index: -1; 
    width: 100%;
}

</style>
<!-- End style css  -->