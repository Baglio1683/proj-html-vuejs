<script>


export default{
    name: 'AppTestimonials', 
    data(){
        return{

        }
    }
}

</script>


<template>

<section>

<div class="container_50 flex_wrap">

    <div class='col_12'>
        <h2>Testimonials</h2>
    </div>

    <div class='col_12'>
    <p>He's what our happy drivers had to say about our services: </p>
    </div>

    <div class='col_12'>
    <img src="../assets/images/testimonial-sophia.png" alt="">
     </div>

    <div class='col_12'>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Autem, similique? Eveniet laborum magni nam quisquam doloribus dolores consectetur delectus atque eos cupiditate! Animi, labore inventore iusto consequuntur magnam rem et?</p> 
    </div>

    <div class='col_12'>
          <h4>Sophia Jones</h4>
    </div>

    <div class='col_12'>
        <a href=""><i class="fa-solid fa-circle"></i></a> <a href=""><i class="fa-regular fa-circle"></i></a> <a href=""><i class="fa-regular fa-circle"></i></a> <a href=""><i class="fa-regular fa-circle"></i></a> <a href=""><i class="fa-regular fa-circle"></i></a>
    </div>

</div>

</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{

background-image: url('../assets/images/testimonial-background.jpg');
background-size: cover;
padding-bottom: 8rem;
color: $color-gumbo;

h2{
    color: $color-tundora;
    font-size: xx-large;
}
.container_50{
    padding-top: 2rem;
    text-align: center;
    img{
        width: 30%;
    }
}

h4{
    font-size: x-large;
}

a{
    color: $color-grayfoot;
    i{
        font-size: small;
    }
}
p{
    line-height: 30px;
}

}


</style>