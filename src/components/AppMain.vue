<script>
import MainSectionOne from './MainSectionOne.vue';
import MainSectionTwo from './MainSectionTwo.vue';
import MainSectionThree from './MainSectionThree.vue';





export default {
  data() {
    return { 
     
    }
  },
   components: {
    MainSectionOne,
    MainSectionTwo,
    MainSectionThree,
    
  },
}
</script>

<template>
  <header>
    <MainSectionOne />
    <MainSectionTwo />
    <MainSectionThree />


   

  </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>
