<template>
  <div>
    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="/images/1.jpg" class="d-block w-100 caro" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/images/2.jpg" class="d-block w-100 caro" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/images/3.jpg" class="d-block w-100 caro" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/images/4.jpg" class="d-block w-100 caro" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/images/5.jpg" class="d-block w-100 caro" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/images/6.jpg" class="d-block w-100 caro" alt="...">
        </div>
        <div class="carousel-item">
          <img src="/images/7.jpg" class="d-block w-100 caro" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
        <span class="carousel-control-prev-icon bg-primary" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
        <span class="carousel-control-next-icon bg-primary" ></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'slider'
}
</script>

<style>
  .caro{
    height: 90vh;
    background-size:cover;
  }
</style>
