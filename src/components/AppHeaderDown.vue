<script>

export default{

    name: 'AppHeaderDown', 
    data(){
        return{

        }
    }
}

</script>


<template>

<section >
    <div class="container justify_space_btw alignIt_center">
        <div>
           <img src="../assets/images/avada-drivers-logo-1x.png" alt="">
        </div>
        <div>
            <ul class="d_flex alignIt_center">
               <li><a href="">HOME</a></li>
               <li><a href="">ABOUT</a></li>
               <li><a href="">PRICES</a></li>
               <li class=""><a href="" class="d_flex gap_2 alignIt_center">COURSES<span class="btn_green_square">NEW</span></a></li>
               <li><a href="">LOCATIONS</a></li>
               <li><a href="">BLOG</a></li>
               <li><a href="" class="btn_green">BOOK NOW</a></li>
            </ul>
        </div>
    </div>
</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{
    background-color: $color-firefly;
    opacity: 0.5;
    font-size: medium;
    font-weight: 900;
    padding: 2rem;
    height: 18vh;

ul{
    list-style: none;
    li{
        margin-right: 15px; 
        font-size: small;
        a{
            text-decoration: none;
            color: white;
        }
    }
}

}

</style>