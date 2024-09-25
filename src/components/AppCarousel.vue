<script>

export default {
  data() {
    return { 
     
    }
  },
   components: {
 
  },
}
</script>

<template>
  <div>
    <div id="" class="carousel" data-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
            <img class="d-block w-100" src="/img/1.jpg" alt="First slide">
            </div>
            <div class="carousel-item ">
            <img class="d-block w-100" src="/img/10.jpg" alt="Second slide">
            </div>
            <div class="carousel-item ">
            <img class="d-block w-100" src="/img/cathryn-lavery-67852-unsplash-544x322.jpg" alt="Third slide">
            </div>
        </div>
        <a class="carousel-control-prev bg-warning" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next bg-primary" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
        </div>
  </div>
 
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;



</style>
