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
  <div class="contaier-xxl d-flex align-items-center justify-content-center p-5">
    <div class="d-flex align-items-center justify-content-center border p-5 me-2">
        <div class="me-3">
            <img src="/public/img/image_box_1-221x231.png" alt="">
        </div>
        <div class="p-5">
            <h4 class="font-size">
                Become an Instructor
            </h4>
            <p class="width">
                Teach what you love. Masterstudy gives you the tools to create a course.
            </p>
            <div>
              <button class="buttonBlue">
                  <a href="@" @click.prevent>
                        START TEACHING
                  </a>
              </button>
            </div>
        </div>
    </div>
    <div class="d-flex align-items-center justify-content-center border p-5 ms-2">
        <div class="me-4">
            <img src="/public/img/image_box_2-234x231.png" alt="foto">
        </div>
        <div class="p-5">
            <h4 class="font-size">
                Setup For Business
            </h4>
            <p class="width">
                Get unlimited access to 2,500 of Udemy’s top courses for your team.
            </p>
            <div>
              <button class="buttonBlue">
                  <a href="@" @click.prevent>
                        DOING BUSINESS
                  </a>
              </button>
            </div>
        </div>
    </div>
   

  </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.buttonBlue{
  @include buttonBlue
}a{
  text-decoration: none;
  color: white;
}.width{
    width: 330px;
}.font-size{
    font-size: 2rem;
}

</style>
