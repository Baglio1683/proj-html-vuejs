<script>

export default{
    name: 'AppFooterTop', 
    data(){
        return{

        }
    }
}

</script>


<template>

    <section>

        <div class="container">

            <div class="col_3">
                <img src="../assets/images/avada-drivers-logo-1x.png" alt="">
                <p>Descriptiom</p>
            </div>

            <div class="col_3">
                <h3>Title</h3>
                <ul>
                    <li>item</li>
                    <li>item</li>
                    <li>item</li>
                </ul>
            </div>

            <div class="col_3">
                <h3>Title</h3>
                <ul>
                    <li>item</li>
                    <li>item</li>
                    <li>item</li>
                </ul>
            </div>
            <div class="col_3">
               <img src="../assets/images/footer-ad-grid.png" alt="">
            </div>

      </div>

    </section>

</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

section{
    background-image: url('../assets/images/footer-background-color.jpg');
    background-size: cover;
}

</style>