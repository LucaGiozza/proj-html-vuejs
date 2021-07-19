<template>
  <div>
      <div class="container-fluid">
          <div class="row">
              <div class="contenitore column-6">
                  <div>
                      <p class="mt-5 free "> <strong>headche free</strong> </p>
                      <h2 class="winning mt-2">Award Winning Moving Company</h2>
                      <p class="lorem mt-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac augue. Orci varius natoque penatibus et magnis dis parturient montes, ridiculus mus. Aliquam enim leo, condimentum facilisis nulla sed, cursus arcu. Aliquam enim leo.</p>
                      <p class="bott mt-4"> <strong>Read our testimonials</strong> </p>
                                     
                  </div>
                  <div class="column-6">
                      <div>
    
                      </div>

                  </div>

              </div>
          </div>

      </div>

  </div>
</template>

<script>
export default {
    name: 'Award'

}
</script>

<style lang="scss" scoped>
.container-fluid{
    background-color:#e9e9e9;
}
.row{
    display:flex;
    justify-content: center;
}
.contenitore{
    max-width:50%;
    text-align: center;
    .winning{
        color:#69bf14;
        margin-bottom:40px;
        
        width: 39%;
        margin-left: 31%;
        text-align: center;
        font-size: 36px;;
    }
    .free{
        padding-top:100px;
        color:rgb(124, 121, 121);
        text-transform: uppercase;
    }
    

}
.lorem{
    color:gray;
    padding-bottom: 20px;
}
.bott{
    padding:5px 10px;
    background-color:#1975c0;
    width:200px;
    margin-left:37%;
    border-radius: 22px; 
    color:white;
    margin-bottom: 80px;
}
.bott:hover{
    filter:brightness(1.20)
}


</style>