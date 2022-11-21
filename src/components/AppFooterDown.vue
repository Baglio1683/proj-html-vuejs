<script>

export default{
    name: 'AppFooterDown', 
    data(){
        return{

        }
    }
}

</script>


<template>
    <section>
        <div class="container">
            <div class="left">
                <i class="fa-solid fa-copyright"></i><span class="f_small">Copyright 2012 - 2020 | Avada Theme by <a href="">ThemeFusion</a> | All Rights Reserved | Powered by <a href="">WordPress</a></span> 
            </div>
            <div class="right">
               <a href=""><i class="fa-brands fa-facebook-f"></i></a>
               <a href=""><i class="fa-brands fa-twitter"></i></a>
               <a href=""><i class="fa-brands fa-youtube"></i></a>
               <a href=""><i class="fa-brands fa-instagram"></i></a>
            </div>
        </div>
    </section>
</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

section{
    background-color: $color-aztec;
    padding-top: 2rem;
    padding-bottom: 2rem; 
    color: $color-gumbo ;
    .container{
      justify-content: space-between;
       .left{
        a{
         color: $color-bay-leaf ;
         text-decoration: none; 
        }
      }
      .right{
        a{
            color: white;
            text-decoration: none;
            margin-right: 15px;
        }
      }  
    }
}

</style>