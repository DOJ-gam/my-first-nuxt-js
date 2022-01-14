<template>
  <div class="">
    <Slider/>

    <!-- About -->
    <About/>

<!-- Services -->
    <Services/>

    <!-- Contact -->
    <div class="py-5">
      <div class="container">
        <div class="row">

          <div class="col-md-8">
            <h1 class="main-heading">If you have any queries</h1>
            <h4>please reach out to us at omarjeng00@gmail.com</h4>
          </div>

          <div class="col-md-4 text-center my-auto">
            <Nuxt-link to="/contact" class="px-5 py-2 btn btn-primary">Contact Us</Nuxt-link>
          </div>

        </div>
      </div>
    </div>

  </div>
</template>

<script>
import Slider from '~/components/Slider.vue'
export default {
  name: 'IndexPage',
  components:{Slider},
  head(){
    return{
      title: 'Home Page',
      meta:[
        {
          hid: 'description',
          name:'description',
          content: 'A simple nuxt and bootstrap 5 website made by DOJ - Daddy Omar Jeng. My first nuxt App, The Home Page!'
        },
        {
          hid: 'keywords',
          name:'keywords',
          content: 'Nuxt, Vue, Javascript, DOJ, Daddy Omar Jeng'
        }
      ]
    }
  },
}
</script>

<style>

</style>
