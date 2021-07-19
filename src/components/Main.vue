<template>
  <div>
      <!-- prima sezione -->
      <section class="award">
          <Award/>

      </section>
      <!-- seconda sezione -->
       <section class="service">
          <Service/>

      </section>
      <!-- terza sezione -->
       <section class="move">
          <Move/>

      </section>
      <!-- quarta sezione -->
       <section class="testimonials">
          <Testimonials/>

      </section>
      <!-- quinta sezione -->
       <section class="request">
          <Request/>

      </section>

  </div>
</template>

<script>
import Award from '@/components/Award.vue'
import Service from '@/components/Service.vue'
import Move from '@/components/Move.vue'
import Testimonials from '@/components/Testimonials.vue'
import Request from '@/components/Request.vue'
export default {
    name: 'Main',
    components:{
        Award,
        Service,
        Move,
        Testimonials,
        Request
    }

}
</script>

<style lang="scss" scoped>
*{
    overflow-x:hidden;
}


</style>