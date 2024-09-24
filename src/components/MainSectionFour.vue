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
  <div class="container-fluid backColor backImg mt-5 ">
    <div class="container d-flex margin-right">
      <div class="d-flex row padding ">

        <div class="col-6">
          <p class="textSection">
            Limitless learning, more possibilities
          </p>
          <p>
            Online courses open the opportunity for learning to almost anyone, regardless of their scheduling commitments.
          </p>
          <a href="#">
            <div  class="buttonBlue" @click.prevent>
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
  font-size: 1.2rem;
}.textSection{
 @include textSection
}.buttonBlue{
  @include buttonBlue
}.backColor{
  background-color: #F0F4FA;
}.backImg{
  background-image: url('/img/Untitled-1-1-1-1-1.png');
  background-repeat: no-repeat;
  background-position:center
}.margin-right{
  margin-right: 200px;
}

</style>
