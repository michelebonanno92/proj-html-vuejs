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
            image : '/public/img/3.jpg',
            preTitle: ' Art' ,
            title: 'Minimalism, How to make things simpler',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '5 hours',
            textRight: '$39.99' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
        },
        {
            image : '/public/img/1photo-1461749280684-dccba630e2f6-272x161.jpeg',
            preTitle: ' Apache' ,
            title: 'Web coding and Apache Basics',
            textLeftOne: ' fa-regular fa-clock ',
            textLeftTwo: '6 hours',
            textRight: 'Free' ,
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
