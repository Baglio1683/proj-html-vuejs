<script>

export default{
    name: 'AppContactBanner', 
    data(){
        return{

        }
    }
}

</script>


<template>

<section>
<div class="container justify_space_btw">

    <div class="col_8">
        <h2>Start to Learning Drive Today</h2>

    </div>

    <div class="col_4">
       <i class="fa-solid fa-phone-flip"></i> 1-800-555-555
    </div>

</div>
</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{
    background-image: url('../assets/images/horizontal-cta-background.jpg');
    background-size: cover;
    color: $color-white; 

    .container{
        padding-top: 2rem;
        padding-bottom: 2rem;
    }

}


</style>