<template>

  
  <div class="posizione" >
    <img class="sfondo" src="@/assets/img/foto27.jpg" alt="">
    <div class="container-fluid">

   
    <div class="row">
      <div class="col-12 text-center">
        <h5 class="mb-4 happy">Happy customers</h5>
        <h2 class="test"> <strong>Testimonials</strong></h2>

      </div>

    </div>
    <div class="row  ">
      <div class="col-4 sinistra foto ">
        <img class="profilo" src="@/assets/img/foto5.jpg" alt="">
        <h5 class="name"> <strong>John Doe</strong> </h5>
        <p>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</p>

      </div>
      <div class="col-4 centro foto ">
         <img class="profilo" src="@/assets/img/foto2.jpg" alt="">
         <h5 class="name"><strong>Jane Doe</strong> </h5>
         <p>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</p>

      </div>
      <div class="col-4 destra foto ">
         <img class="profilo" src="@/assets/img/foto8.jpg" alt="">
         <h5 class="name"><strong>John Smith</strong></h5>
         <p>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</p>

      </div>

    </div>

     <div class="row">
      <div class="col-12 text-center ciao">
        <h6 class="bottone"> <a href="https://avada.theme-fusion.com/movers/testimonials/"><strong>Read more testimonials</strong></a></h6>
        

      </div>

    </div>
     </div>

      
  </div>
</template>

<script>
export default {
  name:'Testimonials'

}
</script>

<style lang="scss" scoped>
*{
  margin:0;
  padding:0;
  box-sizing: border-box;
}
.posizione{
  position: relative;
  padding-bottom: 200px;;
}
.container-fluid{
  
  position: absolute;
  top:10%;
  margin:auto;
  text-align: center;
}
.row{
  text-align: center;
  width:75%;
  margin:auto;
  padding-top:50px;
    .happy{
      color:#797979;
    }
    .test{
      color: #6abf16;
      font-size:45px;
    }
}
.sfondo{
  height: 700px;
  width:100%;
  
}
.profilo{
  border-radius:100px;
  margin-top:70px;
}

// descrizione della foto profilo
.name{
  color:#1975c0;
  padding-top:30px;
}
p{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  color:#797979;
  font-size:14px;
  padding-top:20px;
  max-width:80%;
  margin: auto;
  line-height: 25px;
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
            margin-top:50px;
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
       .posizione{
         overflow:hidden;
       }

       .foto{
         transition: opacity 1s,transform 1s;
       }

       .foto:hover{
         transform: scale(1.3);

       }

</style>