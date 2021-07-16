<template>
  <div>
    <div class="container-fluid">
      <div class="row ">
        <div class="column-12 d-flex header-superiore-container">
           <div class="header-superiore-sx">
             
             <p> <i class="fas fa-phone mx-2"></i> Call us for a Free Quote : 1.800.555.6789</p>
           </div>

           <div class="header-superiore-dx ">
             <i class="fab fa-facebook-f mx-2"></i>
             <i class="fab fa-twitter mx-2"></i>
             <i class="fab fa-instagram mx-2"></i>
             <i class="fab fa-youtube mx-2"></i>

           </div>

        </div>

      </div>

    </div>

  </div>
</template>

<script>
export default {
    name: 'HeaderSuperiore'

}
</script>

<style lang="scss" scoped>
*{
  padding:0;
  box-sizing: border-box;
  margin: 0;
}

.container-fluid{
  background-color: #69bf14;
  height:40px;
  line-height: 40px;
  color:white;
  font-size:13px;
  overflow-x:hidden;
  i{
    color:white;
  }
}
.header-superiore-container{
  justify-content:space-around;
 
}
 i:hover{
  cursor:pointer;
  color:black;
}



</style>