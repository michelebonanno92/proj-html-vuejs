<script>

export default {
  data() {
    return { 
     titleSection: "Recent courses",
     listLink: [
        'All Categories',
        'Art',
        'Exercise',
        'Material Design',
        'Music',
        'Photography',
        'Software Development',
      ],
    }
  },
   components: {
  
  },
}
</script>

<template>
  <div class="container-xxl text-center">
      <p class="textSection mt-5">
        {{ titleSection }}
      </p>
      <ul class="d-flex align-items-center justify-content-center">
          <li v-for="(link, i) in listLink" :key="i" class="me-4 mt-3" >
            <a href="#" @click.prevent>
              {{ link }} 
            </a>
          </li>
        </ul>
        <div class="my-row">
            <div class="my-card bg-warning" v-for="(card, i) in 12" :key="i" >
                CARD
            </div>
           
          
        </div>
   
     
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.textSection{
  @include textSection
}li{
    list-style-type: none;
  }a{
    text-decoration: none;
    font-size: 0.9rem;
  }.my-row{
    display: flex;
    flex-wrap: wrap;
  }
  .my-card{
    width: calc((100% / 6) - 20px );
    height: 300px;
    margin-bottom: 30px;
    margin-left: 10px;
    margin-right: 10px;
  }

</style>
