<script>



export default{

    name: 'AppHeaderTop', 

    data(){
        return{
        }
    }
}

</script>


<template>

<section class="alignIt_center d_flex" >
    <div class="container justify_space_btw">
        <div>We have a 95% Successful Pass Rate!</div>
        <div><a href=""><i class="fa-solid fa-phone-flip"></i>Give us a call to book your tuition ! 1-800-555-555</a></div>
    </div>
</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{
    color: $color-grayfoot; 
    background-color: $color-tundora;
    padding-top: 1rem;
    padding-bottom: 1rem;  
    height: 10vh;
    a{
        color: $color-grayfoot;
        text-decoration: none;
        i{
            margin-right: 15px;
        }
     &:hover{
        color: lightgray;
     }
    }
}

</style>








