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

            <div class="col_12">
                <h3>Latest News</h3>
            </div>

            <div class="col_5">
                <img src="" alt="">
                <h3>title</h3>
                <p>descr 1</p>
                <p>descr 2</p>
            </div>
            <div class="col_5">
                <img src="" alt="">
                <h3>title</h3>
                <p>descr 1</p>
                <p>descr 2</p> 
            </div>

            <div class="col_12">
                <a href="">button</a>
            </div>

        </div>
    </section>


</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

section{

    background-image: url('../assets/images/latestnews-background.jpg');
    background-size: cover;
    .container{
        background-color: $color-white; 
        text-align: center;
    }
}
</style>