<script>


export default {
  data() {
    return { 
     
    }
  
  },
  components: {
      
    }
}
</script>

<template>
    <div class="container-xxl">
      <nav>
        <!-- logo -->
        <div>
          <img src="/img/logo.png" alt="logo" class="me-4">
        </div>

        <!-- search bar + category -->
        <div>
          <div class="d-flex">

            <button type="button">
              <i class="fa-solid fa-bars "></i>
              CATEGORY
            </button>

            <div class="d-flex">
              <input type="text" placeholder="Search courses">
              <span type="button" class="searchBlue">
                <i class="fa-solid fa-magnifying-glass"></i>
              </span>
            </div>

          </div>
        </div>
        <!-- link -->
        <div class="d-flex justify-content-between align-items-center">
          <div class="me-4">
            <a href="#">
              <i class="bi bi-megaphone"></i>
            </a>
            <span >Become an Instructor</span> 
          </div>
          <div>
            <a href="#">
              <i class="bi bi-briefcase"></i>
            </a>
            <span>For Enterprise</span>
          </div>
          
        </div>
          <!-- login + button -->
        <div class="d-flex align-items-center">
          <a href="#">
            <i class="bi bi-person"></i>
            <span> Log in</span>
          </a>
          <a href="#">
            <div  class="buttonBlue">
            SIGN UP
          </div>
          </a>  
          <a href="#">
            <i class="fa-regular fa-heart fa-2xl"></i>
          </a>
         
         
        </div>
      </nav>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
    nav{
      display: flex;
      justify-content: space-between;
      align-items: center;
      a{
        text-decoration: none;
        font-size: 0.7rem;
        margin-right: 10px;
      }
       span{
        font-size: 0.8rem;
      }
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
      }.buttonBlue{
        background-color: $blueColor;
        border: none;
        padding: 10px;
        border-radius: 20px;
        color: white;
        width: 100px;
        text-align: center;
        font-size: 0.7rem;
      }
    }

</style>
