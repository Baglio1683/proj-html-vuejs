<script>

export default{
    name: 'AppCentralBanner' , 
    data(){
        return{

        }
    }
}

</script>

<template>

<div class="container flex_wrap">

    <div class="d_flex justify_center flex_wrap card">
        <div class="circle f_xx_large pos_relative">95%<div class="bar_95"></div></div>
        <h2>Pass Rate</h2>
    </div>

    <div class="d_flex justify_center flex_wrap card">
       <p class="circle f_xx_large pos_relative">100% <div class="bar_100"></div></p>
       <h2>Pass Rate</h2>
    </div>

    <div class="d_flex justify_center flex_wrap card">
        <p class="circle f_xx_large pos_relative">0%<div class="bar_5"></div></p>
        <h2>Pass Rate</h2>
    </div>

    <div class="col_12">
        <h3 class="f_xx_large">Your Instructors</h3>
    </div>

    <div class="col_8">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod, quibusdam quo quas molestias accusantium porro aliquam reprehenderit dolores veniam eveniet libero cum numquam doloribus molestiae blanditiis ea! Dicta, architecto praesentium?</p>
    </div>

    <div class="col_4">
        <a href="" class="btn_green w_100">More about us</a>
    </div>

    <div class="col_4 textalign_center card border_green">
        <img src="../assets/images/instructor-mikehart-200x127.jpg" alt="">
        <h4>Mike Hart</h4>
        <a href=""><i class="fa-brands fa-facebook-f"></i></a> <a href=""><i class="fa-brands fa-twitter"></i></a><a href=""><i class="fa-brands fa-instagram"></i></a>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing </p>
    </div>

    <div class="col_4 textalign_center card border_green">
        <img src="../assets/images/instructor-johnsmith-200x127.jpg" alt="">
        <h4>John Smith</h4>
        <a href=""><i class="fa-brands fa-facebook-f"></i></a> <a href=""><i class="fa-brands fa-twitter"></i></a><a href=""><i class="fa-brands fa-instagram"></i></a>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing </p>
    </div>

    <div class="col_4 textalign_center card border_green">
        <img src="../assets/images/instructor-angelahart-200x127.jpg" alt="">
        <h4>Angela Hart</h4>
        <a href=""><i class="fa-brands fa-facebook-f"></i></a> <a href=""><i class="fa-brands fa-twitter"></i></a><a href=""><i class="fa-brands fa-instagram"></i></a>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing </p>
    </div>

</div>
</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as*; 

.container{
    color: $color-gumbo;

    .card{
        border-radius: 5px;
        box-shadow: 0px 2px 8px 5px rgb(212, 212, 212);
        margin-right: 20px;
        width: calc(100% / 12 * 4 - 20px);
        padding: 1rem;
        padding-top: 50px;
        padding-bottom: 50px;
        margin-bottom: 30px;
        background-color: white;

        &:hover{
            transform: scale(1.2);
        }

        h4{
            margin-top: 10px;
        }

        a{
            display: inline-block;
            color: $color-gumbo;
            margin-right: 5px;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        p{
            line-height: 25px;
        }
    }

    .border_green{
        border-top: 8px solid $color-bay-leaf;
    }

    .circle{
        height: 150px;
        width: 150px;
        line-height: 142px !important;
        text-align: center;
        border-radius: 50%;
        border: 8px solid #F6F6F6;  
    
     }

     .bar_5{
        position: absolute;
        height: 8px;
        width: 5px;
       background-color: $color-bay-leaf ;
       clip-path: circle();
     }
     
     .bar_100{
        position: absolute;
        height: 150px;
        width: 143px;
        border-radius: 50%;
        border: 8px solid $color-bay-leaf ;
     }

     .bar_95{
        position: absolute;
        height: 150px;
        width: 143px;
        border-radius: 50%;
        border: 8px solid $color-bay-leaf ;
        border-top-style: solid;
        border-top-color:  #F6F6F6; 
        top: -4px;
        left: -4px;
        transform: rotate(-45deg);
     }
          
          
            
        
    h2{
        margin-top: 20px;
        margin-bottom: 20px;
        width: 100%;
        text-align: center;
    }

  
   .col_8{
    line-height: 30px;
   }

   .w_100{
    width: 100%;
   }


}


</style>