<template>
  <div>
      <div class="header-superiore">
          <HeaderSuperiore/> 

      </div>
      <div class="header-inferiore">
           <HeaderInferiore/> 

      </div>
      

  </div>
</template>

<script>
 import HeaderSuperiore from '@/components/HeaderSuperiore.vue'
 import HeaderInferiore from '@/components/HeaderInferiore.vue'
export default {
    name: 'Header',
    components: {
        HeaderSuperiore,

        HeaderInferiore,
    
  }

}
</script>

<style lang="scss" scoped>

</style>