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
      <!-- img link -->
      <div class="my-row padding mt-5">
        <div class="myCol60 ">
          <img src="/img/cat_1-770x375.jpg" alt="foto-1">
        </div>

        <div class="myCol30">
          <div>
            <img src="/img/cat_2-370x155.jpg" alt="foto-2">
            <div>
              <div class="d-flex justify-content-between align-items-center mt-1">
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

            </div>
          </div>
          <div class="mt-3">
            <img src="/img/cat_3-370x155.jpg" alt="foto-3">
          </div>
        </div>
        
      </div>
    <!-- title courses delle img di sopra  -->
      <div class="my-row padding">
        <div class="myCol60 mt-2 ">
          <div class="d-flex justify-content-between align-items-center">
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
        <div class="myCol30 mt-2">
          <div class="d-flex justify-content-between align-items-center">
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
      <!-- altre 3 img con i rispettivi link -->
      <!-- foto 4 -->
      <div class="my-row padding mt-4">
        <div class="myCol30">
          <img src="/img/cat_5-370x155.jpg" alt="foto-4">
          <div class="d-flex justify-content-between align-items-center mt-2">
            <div>
              <a href="#" @click.prevent>
                Music
              </a>
            </div>
            <div>
              <a href="#"  @click.prevent class="opacity">
                5 courses
              </a>
            </div>
          </div>
      </div>
      <!-- foto 5 -->
      <div class="myCol30">
        <img src="/img/cat_4-370x155.jpg" alt="foto-5">
        <div class="d-flex justify-content-between align-items-center mt-2">
            <div>
              <a href="#" @click.prevent>
                Exsercise
              </a>
            </div>
            <div>
              <a href="#"  @click.prevent class="opacity">
                7 courses
              </a>
            </div>
          </div>
      </div>
      <!-- foto 6 -->
      <div class="myCol30">
          <img src="/img/cat_6-370x155.jpg" alt="foto-6">
          <div class="d-flex justify-content-between align-items-center mt-2">
            <div>
              <a href="#" @click.prevent>
                Photography
              </a>
            </div>
            <div>
              <a href="#"  @click.prevent class="opacity">
                4 courses
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
  padding: 0 90px;
}.myCol30{
  width: calc(30% - 20px );
  margin-right: 10px;
  margin-left: 10px;
}.myCol60{
  width: calc(60% - 20px );
  margin-right: 10px;
  margin-left: 10px;
}.my-row{
  display: flex;
  flex-wrap: wrap;
  width: 1100px;
}img{
  max-width: 100%;
}a{
  text-decoration: none;
  color: black;
}.opacity{
  opacity: 0.7;
}.margin-right{
  @include margin-right;
}
</style>
