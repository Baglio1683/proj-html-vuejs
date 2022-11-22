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
        <p>Give us a call to schedule your first driving lesson</p>

    </div>

    <div class="col_4">
       <a href=""><i class="fa-solid fa-phone-flip"></i> 1-800-555-555</a>
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

        a{
            font-size: x-large;
            color: white;
            text-decoration: none;
        }

        h2{
            margin-bottom: 12px;
        }
    }

}


</style>