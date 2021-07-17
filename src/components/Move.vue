<template>
  
  <div class="container-fluid">
      <img src="@/assets/img/foto12.jpg" alt="">
      <p>ciao</p>

  </div>
</template>

<script>
export default {
    name: 'Move'

}
</script>

<style lang="scss" scoped>
.container-fluid{
    padding-top:150px;
    height:600px;
    position: relative;
    
    p{
        position: absolute;
        top:50%;
        right: 30%;
    }
}
img{
    width:100%;
    object-fit: cover;
    height: 100%;
    
    
}

</style>