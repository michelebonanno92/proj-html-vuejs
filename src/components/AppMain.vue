<script>
import MainSectionOne from './MainSectionOne.vue';
import MainSectionTwo from './MainSectionTwo.vue';
import MainSectionThree from './MainSectionThree.vue';
import MainSectionFour from './MainSectionFour.vue';
import MainSectionFive from './MainSectionFive.vue';








export default {
  data() {
    return { 
     
    }
  },
   components: {
    MainSectionOne,
    MainSectionTwo,
    MainSectionThree,
    MainSectionFour,
    MainSectionFive,

    
  },
}
</script>

<template>
  <header>
    <MainSectionOne />
    <MainSectionTwo />
    <MainSectionThree />
    <MainSectionFour />
    <MainSectionFive />

    


   

  </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>
