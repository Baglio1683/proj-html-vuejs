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
                <p>Avada Driving SChool is the right choice for experienced drivers looking for a refresher course, or the brand new driver wanting to pass first time.</p>
            </div>

            <div class="col_3">
                <h3>CONTACT DETAILS</h3>
                <ul>
                    <li><a href=""><i class="fa-solid fa-house"></i> 12345 North Main Street, New York, NY 555555</a></li>
                    <li><a href=""><i class="fa-solid fa-phone"></i> 1.800.555.6789</a></li>
                    <li><a href=""><i class="fa-solid fa-envelope"></i> info@your-domain.com</a></li>
                    <li><a href=""><i class="fa-solid fa-link"></i> Theme-Fusion.com</a></li>
                </ul>
            </div>

            <div class="col_3">
                <h3>COURSES</h3>
                <ul>
                    <li><a href=""><i class="fa-regular fa-circle-right"></i> Pass Plus</a></li>
                    <li><a href=""><i class="fa-regular fa-circle-right"></i> Intensive Course</a></li>
                    <li><a href=""><i class="fa-regular fa-circle-right"></i> Automatic</a></li>
                    <li><a href=""><i class="fa-regular fa-circle-right"></i> Instructor Training</a></li>
                </ul>
            </div>
            <div class="col_3 d_flex flex_wrap justify_center">
               <img src="../assets/images/footer-ad-grid.png" alt="">
               <a href="" class="btn_green">BOOK NOW</a>
            </div>

      </div>

    </section>

</template>

<style lang="scss"  scoped>
@use '../styles/partials/variables' as *; 

section{
    background-image: url('../assets/images/footer-background-color.jpg');
    background-size: cover;
    padding-top: 4rem;
    padding-bottom: 4rem;

    .container{
     
    justify-content: flex-start;
    align-items: flex-start;    

    ul{
        list-style: none;
        li{
            margin-bottom: 15px;

            a{
                text-decoration: none;
                line-height: 25px;
                
                span{
                    text-align: left;
                }

                i{
                    margin-right: 5px;
                }
            }
        }
    }
    .col_3{
        p{
            line-height: 25px;
            margin-top: 10px;
            color: $color-gumbo ;
        }
        h3{
            color: white;
            margin-bottom: 20px;
        }
     }

     .col_3:nth-child(2) li a{
        color: $color-gumbo ;
        &:hover{
            color: white;
        }
     }
     .col_3:nth-child(3) li a{
        color: $color-bay-leaf ;
        
        &:hover{
            color: rgb(169, 227, 169)
        }
     }


     .btn_green{
        margin-top: 25px;
     }
    
    }

  }

</style>