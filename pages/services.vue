<template>
  <div class="">
    <div class="py-4 bg-warning">
      <div class="container text-center">
        <h3>Services</h3>
      </div>
    </div>
    <Services/>
  </div>
</template>

<script>
export default {
  name: 'services',
  head(){
    return{
      title: 'Services',
      meta:[
        {
          hid: 'description',
          name:'description',
          content: 'A simple nuxt and bootstrap 5 website made by DOJ - Daddy Omar Jeng. My first nuxt App, The Services Page!'
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
