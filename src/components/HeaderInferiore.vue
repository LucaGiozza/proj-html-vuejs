<template>
  <div class="container-fluid">
      <div class="row">
          <div class="column-12 sm-6 contenitore">
              <img class="jumbotrone" src="@/assets/img/foto1.jpg" alt="">
              <div class="contenuto-jumbo-sx">
                  <img src="@/assets/img/foto11.png" alt="">
              </div>
              <div class="contenuto-jumbo-dx">
                  <ul class="d-flex nav ">
                      <li class="mx-4 green"> <strong>Home</strong> </li>
                      <li class="mx-4"><strong>Rates</strong></li>
                      <li class="mx-4"><strong>Testimonials</strong></li>
                      <li class="mx-4"><strong>FAQ</strong></li>
                      <li class="mx-4"><strong>Blog</strong></li>
                      <li class="mx-4"><strong>Contact</strong></li>
                      <li class="mx-5 bottone">FREE QUOTE</li>
                  </ul>

              </div>
              <div class="contenuto-jumbo-centrale">
                  <p> <strong> Moving without the hassle</strong></p>
                  <h2 class="my-2"><strong>we make it simple</strong></h2>
                  <p><strong> professional service with quality and customer satisfaction</strong></p>

              </div>



          </div>

          
            
                  <div class="banner-header-inferiore">
                         
                      <h4> <i class="fab fa-telegram-plane"></i>get a free quote online now! </h4>

                  </div>
                   

              


          


      </div>
      
  </div>
</template>

<script>
export default {
    name: 'HeaderInferiore'

}
</script>

<style lang="scss" scoped>
*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
}
.container-fluid{
    height:500px;
    
    padding:0;
    
    .jumbotrone{
         height:500px;
         width:100%;

        //  utilizzo objet fit
        object-fit: cover;
      
    }
    .contenuto-jumbo-sx{
        position: absolute;
        top:3%;
        left:4%;
    }
    .contenuto-jumbo-dx{
        position: absolute;
        top:6%;
        right:4%;
        .nav{
            list-style: none;
            .li{
                font-size: 18px;
               
            }
           
        }

    }
    .contenuto-jumbo-centrale{
        position: absolute;
        top:50%;
        left:50%;
        transform:translate(-50%, -50%);
        width: 500px;
        text-align: center;
        text-transform: uppercase;
        p{
            font-size:13px;
            color:rgb(71, 70, 70);
        }
    }
}
.contenitore{
      position:relative;
}
 .bottone{
                color:white;
                background-color: #1975c0;
                padding:11px 32px;
                border-radius:21px;
                margin-top:-11px;
                
        }

    .banner-header-inferiore{
        background-color:#1975c0 ;
        height:150px;
        display:flex;
        justify-content: center;
        vertical-align: middle;
        h4{
            display:flex;
            align-items: center;
            color:white;
            text-transform: uppercase;
            i{
                margin-right: 15px;
                margin-top:8px;
            }
        }
    }
    .contenuto-jumbo-dx ul li:hover{
        color:#69bf14;
        cursor:pointer;
    }
    .green{
        color:#69bf14;
    }
    .contenuto-jumbo-dx ul .bottone:hover{
        color:white;
        cursor:pointer;
       filter: brightness(1.30);
        
    }


</style>