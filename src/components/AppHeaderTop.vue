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
  <div class="container-xxl  size ">
    <nav class="d-flex align-items-center justify-content-between ">

      <div >
        <ul>
          <li >
            <a href="#" class=" d-flex " id="reset">
            English
          <select name="" id="">
          </select>
        </a>
          </li>
        </ul>
      </div>

      <div class="d-flex align-items-center"> 
        
        <ul class="d-flex ">
          <li v-for="(element, i) in listNameNav" :key="i" class="me-3" >
            <a href="#">
              {{ element }} 
            </a>
          </li>
        </ul>
      
        <ul class="d-flex ">
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

header{
  font-family: "Montserrat", sans-serif;
  nav{
    position: relative;
  }
  .size{
    font-size: 0.9rem;
    margin-top: 20px;
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
#reset{
   position: absolute;
   top: 0;
   left: 0;
  }

</style>
