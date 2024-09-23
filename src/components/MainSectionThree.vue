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
    <div class="my-row padding mt-5">
      <div class="myCol60 ">
        <img src="/public/img/cat_1-770x375.jpg" alt="foto-1">
      </div>

      <div class="myCol30">
        <div>
          <img src="/public/img/cat_2-370x155.jpg" alt="foto-2">
          <div>
            <div class="d-flex justify-content-between align-items-center mt-1">
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
        </div>
        <div class="mt-3">
          <img src="/public/img/cat_3-370x155.jpg" alt="foto-3">
        </div>
      </div>
      
    </div>

    <div class="my-row padding">
      <div class="myCol60 ">
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
      <div class="myCol30">
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
    </div>

   </div>

    <!-- <div class="myCol30">
        <i class="fa-regular fa-calendar"></i>
        <p>
          Brand certificate
        </p>
        <p>
          After completing the course, you will receive a certificate confirming your knowledge.
        </p>
      </div>
      <div class="myCol30">
        <i class="fa-regular fa-calendar"></i>
        <p>
          Brand certificate
        </p>
        <p>
          After completing the course, you will receive a certificate confirming your knowledge.
        </p>
      </div>
      <div class="myCol30">
        <i class="fa-regular fa-calendar"></i>
        <p>
          Brand certificate
        </p>
        <p>
          After completing the course, you will receive a certificate confirming your knowledge.
        </p>
      </div> -->
       

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
}
</style>
