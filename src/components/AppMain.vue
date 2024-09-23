<script>
import MainSectionOne from './MainSectionOne.vue';
import MainSectionTwo from './MainSectionTwo.vue';




export default {
  data() {
    return { 
     
    }
  },
   components: {
    MainSectionOne,
    MainSectionTwo,
    
  },
}
</script>

<template>
  <header>
    <MainSectionOne />
    <MainSectionTwo />

   

  </header>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

</style>
