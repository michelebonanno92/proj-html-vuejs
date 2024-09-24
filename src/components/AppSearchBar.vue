<script>
import AppButton from './AppButton.vue';
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
     <div class="d-flex searchw">
              <input type="text" placeholder="Enter your E-mail">
              <span type="button" class="searchBlue">
                  SUBSCRIBE
              </span>
            </div>
        
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

      input{
        background-color: #F0F2F5;
        border: none;
        font-size: 0.8rem;
        padding: 10px;
        width: 400px;
      }.searchBlue{
        background-color: $blueColor;
        color: white;
        width: 150px;
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 0.8rem;
      }.buttonBlue{
        @include buttonBlue
      }input{
        width: 100%;
      }.searchw{
        width: 350px;
      }

</style>
