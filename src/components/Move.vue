<template>
  
  <div class="container-fluid">
      <img src="@/assets/img/foto12.jpg" alt="">
     <div class="green">
         <div class="inside-green">
              <h5> <strong>we remove the headache from moving</strong> </h5>
              <h2><strong>Move whith ease</strong></h2>
              <p>With our super simple service we can take you from getting a quote, right through to being in your new home with all of your belongings securely packed and safely delivered, even in the rooms of your choice. </p>
              <p class="bottone"> <a href="https://avada.theme-fusion.com/movers/free-quote/"><strong>get a free quote now</strong></a> </p>

         </div>
        

     </div>

  </div>
</template>

<script>
export default {
    name: 'Move'

}
</script>

<style lang="scss" scoped>
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}
.container-fluid{
    padding-top:150px;
    height:700px;
    position: relative;
    padding-right:0;
    padding-left:0;
    
  .green{
        
        position: absolute;
        top:26%;
        right: 10%;

        background-color:#21e90f;
        width:450px;
        height:330px;
        border:10px solid #099614;
        .inside-green{
            width:80%;
            font-size:14px;
            margin: auto;
            color:white;
            h5{
                text-transform: uppercase;
                font-size:10px;
                text-align: center;
                padding-top:25px;
                margin-bottom:20px;
                
            }
            h2{
                text-align: center;
                border-bottom: 1px solid white;
                padding-bottom:15px;
            }
            p{
                text-align: center;
                padding-top:15px;
                font-size:12px;
            }
              .bottone{
            display:flex;
            justify-content: center;
            background-color:#1975c0;
            width:220px;
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
        }
    
  }
}
img{
    width:100%;
    object-fit: cover;
    height: 100%;
    
    
}
.bottone:hover{
    filter: brightness(1.25);
}




</style>