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
    <div class="row padding">
      <div class="myCol30  me-4 p-4">
        <i class="fa-solid fa-earth-americas"></i>
        <p>
          Worldwide Trends
        </p>
        <p>
          Our services and collections adhere to cutting-edge solutions in the design world.
        </p>
      </div>
      <div class="myCol30 me-4 p-4">
        <i class="fa-solid fa-desktop"></i>
        <p>
          Complex Online Education
        </p>
        <p>
          We have everything for effective learning and delivery of assignments by students.
        </p>
      </div>
      <div class="myCol30 p-4">
        <i class="fa-regular fa-calendar"></i>
        <p>
          Brand certificate
        </p>
        <p>
          After completing the course, you will receive a certificate confirming your knowledge.
        </p>
      </div>
      
    </div>

  </div>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
.padding{
  padding: 0 100px;
}.myCol30{
  width: 30%;
  background-color: #F2F6FB;
  border-radius: 10px;
}i{
  color: $blueColor;
  font-size: 2.5rem;
}p{
  margin-top: 20px;
}.backColor{
  background-color: #F2F6FB;
}
</style>
