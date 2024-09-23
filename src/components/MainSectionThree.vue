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
  <div class="container">
      <div class="my-row d-flex padding bg-primary">
        <div class="myCol60  me-4">
          <img src="/public/img/cat_1-1540x750.jpg" alt="">
          <div class="d-flex justify-content-between align-items-center mt-2">
            <div>
              <a href="#" @click.prevent>
                Software Development
              </a>
            </div>
            <div>
              <a href="#"  @click.prevent class="opacity">
                5 courses
              </a>
            </div>
          </div>
         
      </div>
      <div class="myCol30 ">
          <img src="/public/img/cat_2-370x155.jpg" alt="foto">
          <div class="d-flex justify-content-between align-items-center mt-2">
            <div>
              <a href="#" @click.prevent>
               Art
              </a>
            </div>
            <div>
              <a href="#"  @click.prevent class="opacity">
                8 courses
              </a>
            </div>
          </div>

          <img src="/public/img/cat_3-370x155.jpg" alt="foto" class="mt-4">
          <div class="d-flex justify-content-between align-items-center mt-2">
            <div>
              <a href="#" @click.prevent>
               Material Design
              </a>
            </div>
            <div>
              <a href="#"  @click.prevent class="opacity">
                5 courses
              </a>
            </div>
          </div>
      </div>
      </div>
  </div>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.padding{
  @include padding
}.myCol30{
  width: 30%;
  background-color: #F2F6FB;
}.myCol60{
  width: 63%;
  background-color: #F2F6FB;
}img{
  max-width: 100%;
}a{
  text-decoration: none;
  color: black;
  font-size: 0.8rem;
}.opacity{
  opacity: 0.7;
}

</style>
