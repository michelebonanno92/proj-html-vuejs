<script>
import AppSearchBar from './AppSearchBar.vue';
export default {
  data() {
    return { 
     titleSection: "We are Pround",
     numberTEXTList: [
        {
            number: '2000',
            text : 'STUDENT',
        },
        {
            number: '950',
            text : 'COURSES',
        },
        {
            number: '1600',
            text : 'HOURS VIDEO',
        },
        {
            number: '150',
            text : 'COUNTRIES REACHED',
        },
     ] ,  
      
    }
  },
   components: {
    AppSearchBar,
  },
}
</script>

<template>
  <div class="container-fluid text-center backgroundImg mt-5  d-flex justify-content-center  ">
    <div class="my-container">
      <p class="textSection mt-5">
        {{ titleSection }}
      </p>
      <p class="font-p">
        Certificate courses are instructed by highly educated and qualified instructors who hold doctoral and master’s level degrees.
      </p>
      <div class="my-row mt-5">
        <div class="bord width-element" v-for="(element ,i) in numberTEXTList" :key="i">
            <div class="title-font">
                {{ element.number }}
            </div>
            <div class="text-font">
                {{ element.text }}
            </div>
        </div>
      
      </div>
        
    </div>
  </div>
  <div class="container-fluid backcolor d-flex justify-content-center align-items-center">
    <div class="my-row">
        <div >
            <p>
                <strong>
                    Subscribe our newsletter
                </strong> 
            </p>
            <p>
                There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words
            </p>
        </div>
        <div >
            <p>
                YOUR E-MAIL ADDRESS
            </p>
            <div>
                <AppSearchBar />
            </div>
        </div>
    </div>
  
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.textSection{
  @include textSection
}.backgroundImg{
  background-image: url('/public/img/we_proud.png');
  background-repeat: no-repeat;
  background-position: bottom;
  background-color: #F0F4FA;
  height: 600px;
}.font-p{
  font-size: 0.9rem;
  width: 580px;
  margin-left: 200px;
}.bord:not(:last-child){
    border-right: 1px solid lightgrey;
}.width-element{
    width: calc(100% / 4);
}.my-row{
    width: 1000px;
    display: flex;
    justify-content: center;
}.title-font{
    font-size: 3rem;
}.text-font{
    font-size: 0.8rem;
    opacity: 0.5;
}.backcolor{
    background-color: #4ED7A8;
    color: white;
    height: 180px;
}
</style>
