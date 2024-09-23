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
  <div class="container-fluid backColor backImg">
    <div class="container  mt-5">
    <div class="d-flex row padding ">

      <div class="col-6">
        <p class="h2f">
          Limitless learning, more possibilities
        </p>
        <p>
          Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments.
        </p>
        <a href="#">
          <div  class="buttonBlue">
            READ MORE
          </div>
         </a> 
      </div>
     
    </div>
  </div>
  </div>

  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
.padding{
  padding: 100px;
}p{
  font-size: 1.4rem;
}.h2f{
  font-size: 4rem;
}.buttonBlue{
  @include buttonBlue
}.backColor{
  background-color: #F0F4FA;
}.backImg{
  background-image: url('/public/img/Untitled-1-1-1-1-1.png');
  background-repeat: no-repeat;
  background-position:bottom
}

</style>
