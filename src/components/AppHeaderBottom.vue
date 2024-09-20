<script>

export default {
  data() {
    return { 
     
    }
  }
}
</script>

<template>
    <div class="container-xxl">
      <nav class="d-flex align-items-center">
        <div>
          <img src="/public/img/logo.png" alt="logo" class="me-4">
        </div>
        <div class="d-flex">
          <button type="button" class="me-2">
            <i class="fa-solid fa-bars"></i>
            CATEGORY
          </button>
          <div class="d-flex justify-content-center">
            <input type="text" placeholder="Search courses">
            <span type="button" class="searchBlue">
              <i class="fa-solid fa-magnifying-glass"></i>
            </span>
          </div>
           
         
        </div>
        <div>
          
        </div>
      </nav>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
    nav{
      img{
        max-width: 200px;
      }
      button{
        border: none;
        background-color: white;
        font-size: 0.8rem;
        font-weight: bold;
        opacity: 0.5;
      }input{
        background-color: #F0F2F5;
        border: none;
        font-size: 0.8rem;
        padding: 10px;
        width: 400px;
      }.searchBlue{
        background-color: $blueColor;
        color: white;
        width: 50px;
        display: flex;
        justify-content: center;
        align-items: center;

      }
    }

</style>
