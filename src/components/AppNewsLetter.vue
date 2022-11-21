<script>

export default{
    name: 'AppNewsLetter' , 
    data(){
        return{

        }
    }
}

</script>


<template>
    <section>
        <div class="container_50 flex_wrap">

            <div class="col_12">
                <h3>Sign up to our Newsletter</h3>
            </div>
            <div class="col_12">
                <input type="text">
            </div>
            <div class="col_12">
                <a href="" class="btn_green">SUBSCRIBE</a>
            </div>
            <div class="col_12">
                <p>(We don't shara your data with anybody, and only use it for its intended purpose)</p>
            </div>

        </div>
    </section>

</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

section{
    background-image: url('../assets/images/newsletter_background.jpg');
    background-size: cover;

    .container_50{
        text-align: center;

        h3{
            font-size: xx-large;
            color: $color-cape-cod;
        }

        input{
            border: 1px solid rgb(192, 192, 192);
            width: 70%;
            height: 30px;
        }
        a{
            width: 70%;
        }

        p{
            color: $color-grayfoot;
            font-size: small;
        }

    }

}

</style>