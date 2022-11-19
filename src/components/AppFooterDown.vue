<script>

export default{
    name: 'AppFooterDown', 
    data(){
        return{

        }
    }
}

</script>


<template>
    <section>
        <div class="container">
            <div>
               link link link 
            </div>
            <div>
               icone icone 
            </div>
        </div>
    </section>
</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

section{
    background-color: $color-aztec; 
    .container{
      justify-content: space-between;  
    }
}

</style>