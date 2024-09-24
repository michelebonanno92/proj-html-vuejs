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
          <li v-for="(link, i) in listLink" :key="i" class="me-5 mt-3" >
            <a href="#" @click.prevent>
              {{ link }} 
            </a>
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
  }a{
    text-decoration: none;
  }

</style>
