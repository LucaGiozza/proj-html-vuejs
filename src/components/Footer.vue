<template>
  <div>
    <!-- footer superiore -->
    <div class="footer-superiore">
      <div class="container">
        <div class="row">
          <div class="col-4">
            <h5 class="about"><strong>about</strong></h5>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis convallis ex ut sem accumsan vehicula. Integer elit arcu, hendrerit id sapien ut, facilisis accumsan arcu.</p>
            <img class="pacchetto" src="@/assets/img/foto14.png" alt="Movers-pack">

          </div>
           <div class="col-4">
             <h5 class="title"><strong>avada movers</strong></h5>
             <ul>
               <li><a href="https://avada.theme-fusion.com/movers/"><i class="fas fa-chevron-right"></i>Home</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/rates/"><i class="fas fa-chevron-right"></i>Rates</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/testimonials/"><i class="fas fa-chevron-right"></i>Testimonials</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/blog/"><i class="fas fa-chevron-right"></i>Blog</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/free-quote/"><i class="fas fa-chevron-right"></i>Free quote</a></li>
             </ul>


          </div>
           <div class="col-4">
             <h5 class="title"><strong>recent posts</strong></h5>
               <ul>
               <li><a href="https://avada.theme-fusion.com/movers/heading-out-to-college/"><i class="fas fa-chevron-right"></i>Heading Out To College?</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/moving-your-business/"><i class="fas fa-chevron-right"></i>Moving Your Business?</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/outstanding-quality/"><i class="fas fa-chevron-right"></i>Outstanding Quality</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/costs-of-moving/"><i class="fas fa-chevron-right"></i>Cost of Moving</a></li>
               <li><a href="https://avada.theme-fusion.com/movers/best-moving-tips/"><i class="fas fa-chevron-right"></i> Best Moving Tips</a></li>
             </ul>

          </div>

        </div>

      </div>

    </div>
    <!-- footer inferiore -->
    <div class="footer-inferiore">
      <p class="copy">@ Copyright 2012-2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
      <p><i class="fab fa-facebook-f"></i> <i class="fab fa-twitter"></i> <i class="fab fa-instagram"></i> <i class="fab fa-youtube"></i></p>


    </div>
   

  </div>
</template>

<script>
export default {
    name: 'Footer',



 

}

</script>

<style lang="scss" scoped>

.footer-superiore{
  height:380px;
}
.row{
  display:flex;
  width:85%;
  margin:auto;
  text-align: left;
}
ul{
  
  li{
    list-style: none;
    padding-top:30px;
     
    a{
      text-decoration: none;
      color:black;
     
    }
    a:hover{
      color:#69bf14;
    }
    i{
      margin-right: 5px;
    }
  }
}

h5{
  padding-top:30px;
  text-transform: uppercase;
}
.title{
  padding-left: 31px;
}
.about{
  margin-bottom:35px;
}

.pacchetto{
  width:180px;
  padding-top:30px;
}


// footer inferiore
.footer-inferiore{
  height: 120px;
  background-color: #69bf14;
  color:white;
  text-align: center;
  .copy{
    padding-top:40px;
    font-size: 12px;
  }
  i{
    margin-right: 20px;
  }


 
}

i:hover{
  cursor:pointer;
  color:black;
}


img:hover{
  filter: drop-shadow(16px 16px 20px black) invert(75%);
}








</style>