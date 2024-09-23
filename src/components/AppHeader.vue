<script>
import AppHeaderTop from './AppHeaderTop.vue';
import AppHeaderBottom from './AppHeaderBottom.vue';



export default {
  data() {
    return { 
     
    }
  },
   components: {
    AppHeaderTop,
    AppHeaderBottom,
  },
}
</script>

<template>
  <header>
    <AppHeaderTop />
    <AppHeaderBottom />

  </header>
</template>
<i class="fa-solid fa-earth-americas"></i>
<i class="fa-solid fa-desktop"></i>
<i class="fa-regular fa-calendar"></i>
<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
header {
  font-family: "Montserrat", sans-serif;
  select{
    border: none;
    opacity: 0.5;
  }li{
    list-style-type: none
  }
}

</style>
