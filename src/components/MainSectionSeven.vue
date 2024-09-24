<script>

export default {
  data() {
    return { 
     titleSection: "Popular courses",

      cards: [
        {
            image : '/public/img/1.jpg',
            preTitle: ' Software Development' ,
            title: 'Basics of Masterstudy Education Theme',  
            textCenter: '5',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/2.jpg',
            preTitle: ' Art' ,
            title: 'Real Things Art Painting by Jason Ni',
            crossedOutPrice: '$60.99',
            textCenter: '5',
            textRight: '$45.99' ,
        },
        {
            image : '/public/img/7.jpg',
            preTitle: ' Art' ,
            title: 'Minimalism, How to make things simpler',
            crossedOutPrice: '$79.99',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '5 hours',
            textRight: '$39.99' ,
        },
        {
            image :  '/public/img/4.jpeg',
            preTitle: ' Electronic' ,
            title: 'Hoe to be a DJ? Make electronic Music',
            crossedOutPrice: '$59.99',
            textCenter: '5',
            textRight: '$49.99' ,
        },
        {
            image : '/public/img/5.jpeg',
            preTitle: ' Communication' ,
            title: 'Graohic Design Basics Masterclass',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '8 hours',
        },
        {
            image : '/public/img/6.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '10 hours',
            textRight: 'Free' ,
        },
        // {
        //     image : '/public/img/7.jpg',
        //     preTitle: ' Art' ,
        //     title: 'Interior design concepts Msterclass',
        //     crossedOutPrice: '$69.99',
        //     textLeftOne: ' fa-regular fa-clock ',
        //     textLeftTwo: '11 hours',
        //     textRight: '$39.99' ,
        // },
        // {
        //     image : '/public/img/8.jpeg',
        //     preTitle: ' Bicycling' ,
        //     title: 'Road Bike Manual or How to Be a Champion',
        //     crossedOutPrice: '$19.99',
        //     textLeftOne: ' fa-regular fa-clock ',
        //     textLeftTwo: '13 hours',
        //     textRight: '$12.99' ,
        // },
        // {
        //     image : '/public/img/9.jpg',
        //     preTitle: ' Documentary' ,
        //     title: 'How to Make Beautiful Landscape photos?',
        //     crossedOutPrice: '$59.99',
        //     textLeftOne: ' fa-regular fa-clock ',
        //     textLeftTwo: '15 hours',
        //     textRight: '$39.99' ,
        // },
        // {
        //     image : '/public/img/10.jpg',
        //     preTitle: ' Art' ,
        //     title: "Let's paint Van Gogh's Starry Night",
        //     crossedOutPrice: '$79.99',
        //     textLeftOne: ' fa-regular fa-clock ',
        //     textLeftTwo: '8 hours',
        //     textRight: '$42.99' ,
        // },
        // {
        //     image : '/public/img/11.png',
        //     preTitle: ' Art' ,
        //     title: 'How to get comforrtable on camera',
        //     textLeftOne: ' fa-regular fa-clock ',
        //     textLeftTwo: '9 hours',
        //     textRight: 'Free' ,
        // },
        // {
        //     image : '/public/img/5.jpeg',
        //     preTitle: ' Fashion' ,
        //     title: 'Fashion Photography from professional',
        //     crossedOutPrice: '$49.99',
        //     textCenter: '5',
        //     textRight: '$29.99' ,
        // },
        
    
    ],

      
    }
  },
   components: {
    
  },
}
</script>

<template>
  <div class="container-fluid backColor pt-5">
    <div class="container-xxl text-center">
      <p class="textSection">
        {{ titleSection }}
      </p>
      <p>
        Discover our most popular courses for self learning
      </p>
      <div class="my-row mt-5">
          <div class="my-card border" v-for="(card, i) in cards" :key="i" >
                  <img :src="card.image" alt="">
              <div class="p-3 text-start">
                  <p class="falseTitle">
                    {{card.preTitle}}
                  </p>
                  <a href="#" @click.prevent>
                      {{card.title}}
                  </a>
                  <hr>
                  <div class="d-flex justify-content-end crossedOutPrice">
                      <s> {{ card.crossedOutPrice }} </s>
                  </div>
                  <div class="d-flex justify-content-between align-items-center">
                      <p>
                          <i :class="card.textLeftOne"></i>
                          {{ card. textLeftTwo }}
                      </p>
                      <p>
                          {{card.textCenter}} 
                      </p>
                      <p>
                          <strong> 
                              {{card.textRight}}
                          </strong>
                      </p>
                    
                  </div>
              
              </div>
          </div>
          
        
      </div>
      <div>
        <button>
            <
        </button>
        <button>
            >
        </button>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.textSection{
  @include textSection
}li{
    list-style-type: none;
  }.my-row{
    display: flex;
    flex-wrap: wrap;
  }.my-card{
    width: calc((100% / 6) - 20px );
    height: 300px;
    margin-bottom: 30px;
    margin-left: 10px;
    margin-right: 10px;
  }.my-card a{
    color: black;
    text-decoration: none;
    font-size: 0.9rem;
  }img{
    max-width: 100%;
  }.falseTitle{
     opacity: 0.4;
  }.crossedOutPrice{
    font-size: 0.7rem;
    opacity: 0.5;
    height: 10px;
  }.backColor{
   background-color: #F0F4FA;
  }button{
    background-color: white;
    border: 1px solid lightgrey;
    opacity: 0.6;
    padding: 10px;
    width: 50px;
    border-radius: 10px;
  }

</style>
