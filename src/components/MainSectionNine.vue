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
  <div class="container-fluid backImg">
    <div class="box">
      <h3 class="titleFont">
        Come as you are
      </h3>
      <p class="fontText">
        MasterStudy used is an excellent workshop whether you come as a counselor, advisor, administrator, or faculty member. I am going home empowered. I am looking forward to attending the On Course MasterStudy and the MasterStudy National Conference next year and facilitating the use of this excellent retention/student success course at my college.
      </p>
      <h5 class="marginText">
        <strong>
          Tim Sab
        </strong> 
      </h5>
      <p>
        General Developer, Stylemix Themes
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

  .backImg{
    background-image: url('/public/img/brooke-cagle-224821-unsplash-1-1920x700.jpg');
    height: 700px;
    position: relative;
  }.box{
    background-color: white;
    height: 550px;
    width: 750px;
    position: absolute;
    top: 90px;
    left: 370px;
    padding-right: 130px;
    padding-left: 80px;
    padding-top: 50px;
  }.titleFont{
    font-size: 2rem;
    margin-bottom: 30px;
  }.marginText{
    margin-bottom: 2px;
    margin-top: 40px;
  }.fontText{
    font-size: 1.2rem;
  }
  
//   .speech-bubble-right:after {
//   border-left-color: #B9B0A7;
//   left: 100%;
//   top: 50%;
//   margin-top: -15px;
// }
// .speech-bubble:after {
//   content: '';
//   position: absolute;
//   width: 0;
//   height: 0;
//   border: 15px solid;
//   color: white;
// }

// .speech-bubble{
//   position: relative;
// }
</style>
