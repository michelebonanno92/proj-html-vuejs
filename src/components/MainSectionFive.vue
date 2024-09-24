<script>

export default {
  data() {
    return { 
     titleSection: "Recent courses",
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
      <ul>
        <li>

        </li>
      </ul>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.textSection{
  @include textSection
}li{
    list-style-type: none;
  }

</style>
