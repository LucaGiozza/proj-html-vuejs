<template>
  <div class="sezione-request text-center">
    <div>
      <img src="@/assets/img/foto13.jpg" alt="">

    </div>
    <div class="request-text">
      <h2><strong>Request A Free Quote</strong></h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
      <span class="bottone"><a href=""><strong>Click here</strong></a></span>

    </div>
      
  </div>
</template>

<script>
export default {
  name : 'Request'

}
</script >

<style lang="scss" scoped>
.sezione-request{
  
  position: relative;
  width:100%;
  margin:auto;

}
img{
  height:450px;
  border-bottom:7px solid #69bf14;
}
.request-text{
  position: absolute;
  top:35%;
  left: 26%;
  width: 754px;
    h2{
      color:#69bf14;
      padding-bottom: 20px;
     
    }
  
}
  .bottone{
            display:flex;
            justify-content: center;
            background-color:#1975c0;
            width:150px;
            margin: auto;
            border-radius: 18px;
            padding: 10px 2px;
            cursor: pointer;
            margin-bottom:20px;
            margin-top:30px;
            a{
                 text-transform: uppercase;
                 font-size:13px;
                 color:white;
                 text-decoration: none;
            }
           
        }
        .bottone:hover{
          filter: brightness(1.25);
       }

</style>