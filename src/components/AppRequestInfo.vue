<script>

export default{
    name: 'AppRequestInfo', 
    data(){
        return{

        }
    }
}

</script>


<template>
    <div class="container">

        <div class="col_6">
            <h2>Get Behind The Wheel</h2>
            <p class="line_height_30">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est voluptatum voluptas fugiat esse similique tenetur, accusantium porro cum, maxime perspiciatis eveniet accusamus, reiciendis veniam fuga deserunt et reprehenderit aspernatur. Ducimus?</p>
            <p class="f_small line_height_25">Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta odio, quisquam nam aliquid dolore quam neque harum fugiat voluptates sit? Dolores quasi maxime amet cum a numquam blanditiis quam nisi!</p>
        </div>

        <div class="col_6">

            <h2>First Lesson Free</h2>
            <p>When you make a block booking with us </p>

        </div>

    </div>
</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

    .container{
        p{
            margin-top: 15px;
            color: $color-grayfoot;
        }
         
        .col_6:nth-child(1){
            padding-top: 50px;
            padding-bottom: 100px;
     }

    }

</style>