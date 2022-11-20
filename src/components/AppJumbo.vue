<script>


export default{
    name: 'AppJumbo' , 
    data(){
        return{

        }
    }
}

</script>


<template>

 <div class="jumbo d_flex alignIt_center">
    <div class="container flex_wrap">
        <h1 class="col_12">Drive with Avada</h1>
        <p class="col_12">We offer the finest driving tuition money can buy</p>
    </div>
</div>

</template>

<style lang="scss"  scoped>

   .jumbo{
    background-image: url('../assets/images/homepage-hero-background.jpg');
    background-size: cover;
    height: 120vh;
    width: 100%;
    color: white;
    font-size: xx-large;
   }

</style>