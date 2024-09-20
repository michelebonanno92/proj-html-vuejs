<script>
export default {
  data() {
    return { 
      listNameNav: [
        'Courser',
        'Zoom',
        'Pages',
        'Bundles',
        'Course Formats',
        'Add Course',
        'Demos',
      ],
      listIcons: [
        'fab fa-twitter',
        'fab fa-instagram',
        'fab fa-behance',
        'fab fa-dribbble',
        'fab fa-flickr',
        'fab fa-git',
        'fab fa-linkedin',
        'fab fa-pinterest',
      ]
    }
  }
}
</script>

<template>
  <div class="container-xxl r size">
    <nav class="d-flex align-items-strech">

      <div class="d-flex flex-grow-1 ">
        <a href="#" class=" d-flex  align-items-center">
          English
          <select name="" id="">
          </select>
        </a>
      </div>

      <div >
        <ul class="d-flex align-items-stretch">
          <li v-for="(element, i) in listNameNav" :key="i" class="me-3" >
            <a href="#">
              {{ element }} 
            </a>
          </li>
        </ul>
      </div>
      
      <div>
        <ul class="d-flex align-items-stretch">
          <li v-for="(icon, i) in listIcons" :key="i" class="me-2" >
            <a href="#"  >
              <i :class="icon"></i>
            </a>
          </li>
        </ul>
      </div>
      
    </nav>
  </div>
 
 
  <hr>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
header {
  font-family: "Montserrat", sans-serif;
  .size{
    font-size: 0.9rem;
  }
  select{
    border: none;
    opacity: 0.5;
    cursor: pointer;
  }
  li{
    list-style-type: none;
  }
  a{
    text-decoration: none;
    color: black;
    opacity: 0.5;
  }
 
}

</style>
