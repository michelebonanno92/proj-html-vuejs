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
  <div class="container margin-right">
    <div class="d-flex justify-content-center align-items-center row padding">

      <div class="col-7 margin-top">
        <p class="h2f">
          Start Investing in You
        </p>
        <p>
          With over 1200 courses in 18 subjects, you're guaranteed to find something that's right for you.
        </p>
        <a href="#">
          <div  class="buttonBlue">
            JOIN FOR FREE
          </div>
         </a> 
      </div>

      <div class="col-5">
        <img src="/img/base.png" alt="base">
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
}img{
  max-width: 100%;
}.margin-top{
  margin-top: 80px;
}.margin-right{
  @include margin-right;
}
</style>
