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
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolores totam quod doloribus, culpa corporis obcaecati fugit maxime sed. Reprehenderit velit consectetur, reiciendis aspernatur veniam dicta tempore sed doloribus architecto voluptates!</p>
    </div>

    <div class='col_12'>
    <img src="" alt="">
     </div>

    <div class='col_12'>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Autem, similique? Eveniet laborum magni nam quisquam doloribus dolores consectetur delectus atque eos cupiditate! Animi, labore inventore iusto consequuntur magnam rem et?</p> 
    </div>

    <div class='col_12'>
          <h4>Name and surname</h4>
    </div>

    <div class='col_12'>
        <a href="">link</a>
    </div>

</div>

</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{

background-image: url('../assets/images/testimonial-background.jpg');
background-size: cover;
.container_50{
    padding-top: 2rem;
    text-align: center;
}

}


</style>