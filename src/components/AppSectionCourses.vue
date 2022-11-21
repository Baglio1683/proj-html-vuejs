<script>


export default{
    name: 'AppSectionCourses', 
    data(){
        return{

        }
    }
}

</script>


<template>

<section>

  <div class="container">

     <div class="col_6 d_flex justify_center flex_wrap">
        <h2>Courses</h2>
        <p class="textalign_center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam illo placeat magnam magni totam veniam tempore delectus, molestias quam aperiam iusto, fugit ipsum atque qui quisquam cupiditate? Tenetur, unde accusamus.</p>
        <a href="" class="btn_green">COURSE INFORMATION</a>
     </div>
    
     <div class="col_2 card d_flex justify_center flex_wrap">
        <img src="../assets/images/courses-passplus-200x200.jpg" alt="">
        <h4>Pass Plus</h4>
        <a href="" class="btn_gumbo">LEARN MORE</a>

     </div>

     <div class="col_2 card d_flex justify_center flex_wrap">
        <img src="../assets/images/course-intensive-200x200.jpg" alt="">
        <h4>Intensive Course</h4>
        <a href="" class="btn_gumbo">LEARN MORE</a>
     </div>


    <div class="col_2 card d_flex justify_center flex_wrap">
        <img src="../assets/images/courses-instructor-200x200.jpg" alt="">
        <h4>Instructors</h4>
        <a href="" class="btn_gumbo">LEARN MORE</a>
    </div>

  </div>

</section>

</template>

<style lang="scss"  scoped>
@use "../styles/partials/variables" as *;

section{
   background-image: url('../assets/images/promise-background.jpg');
   background-size: contain;
   background-repeat: no-repeat;
   background-color: $color-athens-gray;
   padding-bottom: 4rem;
   .container{

       img{
         height: 100px;   
         width: 100px;
       }
      .col_6{
         box-shadow: 5px 10px 18px $color-grayfoot;
         background-color: white;
         border-radius: 5px;
         padding-bottom: 50px;
         padding-left: 3em;
         padding-right: 3em;
         padding-top: 50px;
         position: relative;
         top: -30px;
         left: 0;

         p{
         color: $color-grayfoot;
         line-height: 30px;
         margin-top: 20px;
         margin-bottom: 20px;
         }
      }

      .col_2{
         color: $color-gumbo;
         h4{
            padding-top: 10px;
            padding-bottom: 10px;
         }
      }

      .btn_gumbo{
       font-size: 10px;
      }
}
}

</style>