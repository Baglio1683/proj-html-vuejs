<script>

export default{
    name: 'AppLatestNews' , 
    data(){
        return{

        }

    }

}

</script>


<template>

    <section>
        <div class="container flex_wrap">

            <div class="col_12 alignIt_center">
                <h2>Latest News</h2>
            </div>

            <div class="col_6">
                <img src="../assets/images/blog-choosecar-320x202.jpg" alt="">
                <h3>What Car to Start With</h3>
                <p class="f_small">February 7th, 2019 | 0 Comments</p>
                <p class="descr_card">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <div class="col_6">
                <img src="../assets/images/blogpost-10and2-320x202.jpg" alt="">
                <h3>Avada Driving School Expanding</h3>
                <p class="f_small">February 7th, 2019 | 0 Comments</p>
                <p class="descr_card">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>

            <div class="col_12">
                <a href="" class="btn_green">MORE FROM THE BLOG</a>
            </div>

            <img src="../assets/images/latestnews-bottom-1200x105.png" alt="" class="arrow_down">

        </div>
    </section>


</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

section{

    background-image: url('../assets/images/latestnews-background.jpg');
    background-size: cover;
    padding-top: 2rem;
    padding-bottom: 5rem;

    .container{
        border-top: 8px solid $color-gumbo;
        border-top-left-radius: 5px;
        border-top-right-radius: 5px;
        position: relative;
        top: -60px;
        background-color: $color-white; 
        text-align: center;
        .arrow_down{
            position: absolute;
            bottom: -82px;
        }

        h2{
        color: $color-cape-cod;
        font-size: xx-large;
       }

     .descr_card{
        margin-top: 10px;
     }
    .col_6{
        h3{
            color: $color-bay-leaf;
            margin-top: 10px;
        }
        p{
            color: $color-cape-cod; 
        }
     }


    }
}


</style>