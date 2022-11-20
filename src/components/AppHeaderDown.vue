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

    <a href="" class="white_square d_flex flex_wrap justify_center">
      <i class="fa-solid fa-square-caret-up"></i>
      <p class="f_small">Demos</p>
    </a>

    <a href="" class="white_square d_flex flex_wrap justify_center">
        <div><span class="f_small">$</span> <span class="vertical_al_sub">39</span></div> 
        <p class="f_small">On Sale</p>
    </a>

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
    position: relative;

.white_square{
    position: absolute;
    right: 5px;
    bottom: -15px;
    text-decoration: none;
    color: $color-tundora;
    padding-top: 5px;
}

.white_square:nth-child(2){
    position: absolute;
    right: 5px;
    bottom: -70px;
    span{
        color : $color-bay-leaf; 
    }
}


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