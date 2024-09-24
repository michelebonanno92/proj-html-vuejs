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
    <button class="buttonBlue">
      <a href="@" @click.prevent>
        SHOW ALL
      </a>
    </button>
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.buttonBlue{
  @include buttonBlue
}a{
  text-decoration: none;
  color: white;
}

</style>
