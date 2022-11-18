<script>

export default{

    name: 'AppHeaderDown', 
    data(){
        return{

        }
    }
}

</script>


<template>

<section>
    <div class="container justify_space_btw">
        <div>
           <img src="../assets/images/avada-drivers-logo-1x.png" alt="">

        </div>
        <div>
            <ul class="d_flex">
               <li>item</li>
               <li>item</li>
               <li>itm</li>
               <li>itm</li>
               <li>itm</li>
               <li>itm</li>
               <li>itm</li>
            </ul>
        </div>
    </div>
</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{
    background-color: $color-firefly;
    opacity: 0.5;
    color: $color-white;
    padding: 2rem;
    height: 18vh;

ul{
    list-style: none;
    li{
        margin-right: 5px; 
    }
}

}

</style>