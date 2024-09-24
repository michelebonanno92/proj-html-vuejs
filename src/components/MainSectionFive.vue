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

      cards: [
        {
            image : '/public/img/1.jpg',
            preTitle: ' Software Development' ,
            title: 'Basics of Masterstudy Education Theme',
            textLeftOne: 'fa-solid fa-star',
            textLeftTwo: '1',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/2.jpg',
            preTitle: ' Art' ,
            title: 'Real Things Art Painting by Jason Ni',
            textLeftOne:  'fa-solid fa-star' ,
            textLeftTwo: '1',
            textRight: '$45.99' ,
        },
        {
            image : '/public/img/7.jpg',
            preTitle: ' Art' ,
            title: 'Minimalism, How to make things simpler',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '5 hours',
            textRight: '$39.99' ,
        },
        {
            image :  '/public/img/4.jpeg',
            preTitle: ' Electronic' ,
            title: 'Hoe to be a DJ? Make electronic Music',
            textLeftOne: 'fa-solid fa-star',
            textLeftTwo: '1',
            textRight: '$49.99' ,
        },
        {
            image : '/public/img/5.jpeg',
            preTitle: ' Communication' ,
            title: 'Graohic Design Basics Masterclass',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '8 hours',
            textRight: '' ,
        },
        {
            image : '/public/img/6.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '10 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/7.jpg',
            preTitle: ' Art' ,
            title: 'Interior design concepts Msterclass',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '11 hours',
            textRight: '39.99' ,
        },
        {
            image : '/public/img/8.jpeg',
            preTitle: ' Bicycling' ,
            title: 'Road Bike Manual or How to Be a Champion',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '13 hours',
            textRight: '$12.99' ,
        },
        {
            image : '/public/img/9.jpg',
            preTitle: ' Documentary' ,
            title: 'How to Make Beautiful Landscape photos?',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '15 hours',
            textRight: '$39.99' ,
        },
        {
            image : '/public/img/10.jpg',
            preTitle: ' Art' ,
            title: "Let's paint Van Gogh's Starry Night",
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '8 hours',
            textRight: '$42.99' ,
        },
        {
            image : '/public/img/11.png',
            preTitle: ' Art' ,
            title: 'How to get comforrtable on camera',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '9 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/5.jpeg',
            preTitle: ' Fashion' ,
            title: 'Fashion Photography from professional',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '',
            textRight: '$29.99' ,
        },
        
    
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
          <li v-for="(link, i) in listLink" :key="i" class="me-4 mt-3" >
            <a href="#" @click.prevent>
              {{ link }} 
            </a>
          </li>
        </ul>
        <div class="my-row">
            <div class="my-card border" v-for="(card, i) in cards" :key="i" >
                    <img :src="card.image" alt="">
                <div class="p-3 text-start">
                    <p class="falseTitle">
                      {{card.preTitle}}
                    </p>
                    <a href="#">
                        {{card.title}}
                    </a>
                    <hr>
                    <div class="d-flex justify-content-between align-items-center">
                        <p>
                            <i :class="card.textLeftOne"></i>
                            {{ card.textLeftTwo }}
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
    font-size: 0.9rem;
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
  }img{
    max-width: 100%;
  }.falseTitle{
     opacity: 0.4;
  }p{
    font-size: 0.8rem;
  }

</style>
