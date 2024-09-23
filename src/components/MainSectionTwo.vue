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
  <div class="container-xxl">

    <div class="row g-lg-4 padding ">
      <div class="myCol30">
        <div class="p-3 border">
          <div>
            <i class="fa-solid fa-earth-americas"></i>
          </div>
          <p>
            Worldwide Recognize
          </p>
          <p>
            Our online course certificates can be used around the world and also in most popular universities and companies.
          </p>
        </div>
      </div>

      <div class="myCol30">
        <div class="p-3 border">
          <div>
            <i class="fa-solid fa-desktop"></i>
          </div>
          <p>
            Mostly Online Learning (sd)
          </p>
          <p>
            Masterstudy online certificates can be obtained in a range of specialized areas and typically take about a year to complete.
          </p>
        </div>
      </div>

      <div class="myCol30">
        <div class="p-3 border">
          <div>
            <i class="fa-regular fa-calendar"></i>
          </div>
          <p>
             Graduate in as little as 1 Year
          </p>
          <p>
           Online post-graduate certificates are a popular way to develop your professional qualifications of Masterstudy.
          </p>
        </div>
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
  height: 300px;
}i{
  color: $blueColor;
  font-size: 2.5rem;
}p{
  margin-top: 20px;
}.backColor{
  background-color: #F2F6FB;
}
</style>
