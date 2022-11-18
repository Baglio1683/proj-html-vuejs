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

<section>
    <div class="container justify_space_btw">
        <div>We have a 95% Successful Pass Rate!</div>
        <div><i class="fa-solid fa-phone-flip"></i>Give us a call to book your tuition! 1-800-555-555</div>
    </div>
</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{
    background-color: $color-tundora;
    padding: 1rem;
    color: $color-akaroa;    
    height: 10vh;
}

</style>