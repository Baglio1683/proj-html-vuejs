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
        <p class="circle f_xx_large">95%</p>
        <h2>Pass Rate</h2>
    </div>

    <div class="d_flex justify_center flex_wrap card">
       <p class="circle f_xx_large">100%</p>
       <h2>Pass Rate</h2>
    </div>

    <div class="d_flex justify_center flex_wrap card">
        <p class="circle f_xx_large">5%</p>
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

    <div class="col_4 textalign_center card">
        <img src="../assets/images/instructor-mikehart-200x127.jpg" alt="">
        <h4>Mike Hart</h4>
        <a href="">links</a>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing </p>
    </div>

    <div class="col_4 textalign_center card">
        <img src="../assets/images/instructor-johnsmith-200x127.jpg" alt="">
        <h4>John Smith</h4>
        <a href="">links</a>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing </p>
    </div>

    <div class="col_4 textalign_center card">
        <img src="../assets/images/instructor-angelahart-200x127.jpg" alt="">
        <h4>Angela Hart</h4>
        <a href="">links</a>
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
    }
    .circle{
        position: relative;
        height: 150px;
        width: 150px;
        line-height: 142px;
        text-align: center;
        border-radius: 50%;
        border: 8px solid $color-bay-leaf; 
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