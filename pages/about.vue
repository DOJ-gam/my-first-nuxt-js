<template>
  <div class="">
    <div class="py-4 bg-warning">
      <div class="container text-center">
        <h3>About</h3>
      </div>
    </div>

    <About/>
  </div>
</template>

<script>
export default {
  name: 'about',
  head(){
    return{
      title: 'About Us',
      meta:[
        {
          hid: 'description',
          name:'description',
          content: 'A simple nuxt and bootstrap 5 website made by DOJ - Daddy Omar Jeng. My first nuxt App, The Avout Us Page!'
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
