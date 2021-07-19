<template>
  
  <div>
      <div class="container">
          <div class="row">
              <div class="column-12">
                  <div class="text-center">
                      <p class="prof ">we are professional</p>
                      <h2 class="full"> <strong>Full-service solution</strong> </h2>
                  </div>

              </div>

          </div>

          <!-- tre colonne -->
          <div class="container-fluid d-flex">
              <div class="row">
                  <div class=" first">
                      <img src="@/assets/img/foto16.jpg" alt="">
                      
                      <div class="descrizione">
                          <h3><strong>Two man teams</strong> </h3>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
                          <span class="bottone"><a href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=QDY0PkXpqxyLUIh0Hl2wPz%3ALUkByI-QBH2hrTM0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius"><strong>read more</strong></a> </span>
                      </div>
                      

                  </div>
                  </div>

                   <div class="row">
                  <div class=" first">
                      <img src="@/assets/img/foto24.jpg" alt="">
                      <div class="descrizione">
                          <h3> <strong>We do all the lifting</strong> </h3>
                      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
                           <span class="bottone"><a href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=QDY0PkXpqxyLUIh0Hl2wPz%3ALUkByI-QBH2hrTM0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius"><strong>read more</strong></a> </span>
                      </div>
                      

                  </div>
                  </div>
                  <div class="row">
                  <div class=" first">
                       <img src="@/assets/img/foto20.jpg" alt="">
                       <div class="descrizione">
                            <h3> <strong>Coast to coast</strong> </h3>
                       <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
                       
                           <span class="bottone"><a href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=QDY0PkXpqxyLUIh0Hl2wPz%3ALUkByI-QBH2hrTM0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius"><strong>read more</strong></a></span>

                       
                           
                       </div>
                      

                      

                  </div>
                  </div>
              

          </div>

      </div>

  </div>
</template>

<script>
export default {
    name:'Service'

}
</script>

<style lang="scss" scoped>
.prof{
    
    text-transform: uppercase;
    padding-top:100px;
    color:#afaeae;
}
.full{
    color: #69bf14;
}
.row{
    justify-content: center;
    width:100%;
    padding-top:100px;
}
img{
    
    border:10px solid #e9e9e9;
    

        
    
}
.first{
    margin-right:30px;
    margin-left:-15px;
    
    
    h3{
        max-width: 90%;
        padding:20px 0;
        color:#1975c0;
        text-align: center;
        
    }
    p{
        max-width: 80%;
        margin:auto;
        padding-bottom:30px;
    }
    .descrizione{
        border-right:10px solid #e9e9e9;
        border-left:10px solid #e9e9e9;
        border-bottom:10px solid #e9e9e9;
        margin-right:10px;
        width:419px;
        .bottone{
            display:flex;
            justify-content: center;
            background-color:#1975c0;
            width:160px;
            margin: auto;
            border-radius: 18px;
            padding: 10px 2px;
            cursor: pointer;
            margin-bottom:20px;
            a{
                 text-transform: uppercase;
                 font-size:13px;
                 color:white;
                 text-decoration: none;
            }
           
        }
       
        
    }
}

// hover
  .bottone:hover{
                filter: brightness(1.25);
            }


*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}



</style>