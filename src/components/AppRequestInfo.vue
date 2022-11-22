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

        <div class="col_6 d_flex flex_wrap request_card justify_center">

            <h2 class="col_12 textalign_center">First Lesson Free</h2>
            <p class="col_12 textalign_center">When you make a block booking with us your first lesson is included free.</p>
            <input type="text" name="" id="" placeholder="Your name*" class="col_12">
            <input type="text" placeholder="Email*" class="col_12">
            <input type="text" placeholder="Telephone*" class="col_12">
            <input type="text" placeholder="Location*" class="col_12">
            <a href="" class="btn_green">REQUEST A CALLBACK</a>

        </div>

    </div>
</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

    .container{
        position: relative;

        p{
            margin-top: 15px;
            color: $color-grayfoot;
        }
         
        .col_6:nth-child(1){
            padding-top: 50px;
            padding-bottom: 100px;

            h2{
              color: $color-tundora;
            }
         }

     .col_6:nth-child(2){
            border-radius: 5px;
            position: absolute;
            top: -20px;
            right: 0;
            background-color: white;
            box-shadow: 5px 10px 18px $color-grayfoot;
            
            h2{
                color: $color-bay-leaf;
                padding: 10px;
                }

            p{
                padding: 10px;
                margin: 0;
            }
        
        

            input{
                margin-bottom: 15px;
                height: 15px;
                border: 1px solid rgb(200, 197, 197);
                border-radius: 5px;
                background-color: #F7F7F7;
               
            }

            input::placeholder{
                color:$color-grayfoot;
     }

    }
    }

</style>