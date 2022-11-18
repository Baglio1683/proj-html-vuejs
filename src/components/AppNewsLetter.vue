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
                <h3>Title</h3>
            </div>
            <div class="col_12">
                <input type="text">
            </div>
            <div class="col_12">
                <a href="">button</a>
            </div>
            <div class="col_12">
                <p>Description</p>
            </div>

        </div>
    </section>

</template>

<style lang="scss"  scoped>

section{
    background-image: url('../assets/images/newsletter_background.jpg');
    background-size: cover;

    .container_50{
        text-align: center;

    }

}

</style>