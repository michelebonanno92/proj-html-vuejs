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
