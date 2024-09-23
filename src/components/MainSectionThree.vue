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
      <div class="myCol60  p-4">
        
      </div>
      <div class="myCol30  p-4">
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
      <div class="myCol30 p-4">
        <i class="fa-regular fa-calendar"></i>
        <p>
          Brand certificate
        </p>
        <p>
          After completing the course, you will receive a certificate confirming your knowledge.
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
  padding: 0 90px;
}.myCol30{
  width: calc(30% - 20px );
  background-color: #F2F6FB;
  margin-right: 10px;
  margin-left: 10px;
}.myCol60{
  width: calc(60% - 20px );
  background-color: #F2F6FB;
  margin-right: 10px;
  margin-left: 10px;
}i{
  color: $blueColor;
  font-size: 2.5rem;
}p{
  margin-top: 20px;
}.backColor{
  background-color: #F2F6FB;
}.my-row{
  display: flex;
  flex-wrap: wrap;
  width: 1100px;
}
</style>
