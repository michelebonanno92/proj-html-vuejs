<script>
export default {
  data() {
    return { 
      listNameNav: [
        'Menu'
      ]
    }
  }
}
</script>

<template>
  <header>
    <nav class="d-flex justify-content-between col-12">
      <div>
        English 
        <select name="" id="">
        </select>
      </div>
      <ul>
        <li></li>
      </ul>
    </nav>
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
