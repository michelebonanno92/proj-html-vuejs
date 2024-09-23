<script>
export default {
  data() {
    return { 
      listBox : [
        boxOne = {
          icon : '<i class="stmlms-world"></i>',
          pOne: 'lorem gaodoofoo',
          pTwo: ' lorehghghghghhghghghghghghg',

        },
        boxTwo = {
          icon : 'fab fa-twitter',
          pOne: 'lorem gaodoofiiiiiiiiiioo',
          pTwo: ' lorehghghghghhghhhhhhghghghghghg',

        },
        boxThree = {
          icon : '<i class="stmlms-world"></i>',
          pOne: 'lorem gaodoohhhhhhhfoo',
          pTwo: ' lorehghghghghhghghhhhhhhghghghghg',

        },
      ]
    }
  },
   components: {
  
  },
}
</script>

<template>
  <div class="container-xxl">

    <div class="row g-lg-4 padding ">
      <div class="my-col-33" v-for="(box,i) in listBox" :key="i">
        <div class="p-3 border bg-light">
          <a href="#"  >
              <i :class="icon"></i>
            </a>
          <p>
            {{ box.pOne }}
          </p>
          <p>
            {{ box.pTwo }}
          </p>
        </div>
      </div>
   
    </div>

  </div>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
.padding{
  padding: 0 100px;
}.my-col-33{
  width: 30%;
}
</style>
