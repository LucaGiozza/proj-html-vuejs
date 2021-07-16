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
                      <p>ciao</p>

                  </div>
                  </div>

                   <div class="row">
                  <div class="column-4 first">
                      <p>ciao</p>

                  </div>
                  </div>
                  <div class="row">
                  <div class="column-4 first">
                      <p>ciao</p>

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
    color:#7c7979;
    text-transform: uppercase;
    padding-top:100px;
}
.full{
    color: #69bf14;
}
.row{
    justify-content: center;
    width:100%;
    padding-top:100px;
}
.first{
    width: calc(100% / 3 )
}


</style>