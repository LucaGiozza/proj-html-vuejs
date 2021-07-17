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
                  <div class="column-4 first">
                      <img src="@/assets/img/foto16.jpg" alt="">
                      
                      <div class="descrizione">
                          <h3><strong>Two man teams</strong> </h3>
                          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>

                      </div>
                      

                  </div>
                  </div>

                   <div class="row">
                  <div class="column-4 first">
                      <img src="@/assets/img/foto24.jpg" alt="">
                      <div class="descrizione">
                          <h3> <strong>We do all the lifting</strong> </h3>
                      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>

                      </div>
                      

                  </div>
                  </div>
                  <div class="row">
                  <div class="column-4 first">
                       <img src="@/assets/img/foto20.jpg" alt="">
                       <div class="descrizione">
                            <h3> <strong>Coast to coast</strong> </h3>
                       <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>

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
    
    border:15px solid #e9e9e9;
    

        
    
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
    }
    .descrizione{
        border:15px solid #e9e9e9;
        margin-right:30px;
        
    }
}


</style>