<script>
export default {
  data() {
    return { 
    //  listUlElements: [
    //     {
    //         title: 'About',
    //         textOne : 'Masterstudy is Education WordPress theme featured by Learning Management System (LMS) for online education.',
    //         textTwo: 'Developed by StylemixThemes.',
    //         textThree: '',
    //     },

    //  ],
    }
  },
   components: {
 
  },
}
</script>

<template>
  <Footer class="d-flex">
    <div class="container-xxl d-flex justify-content-between mt-5 ">
        <!-- About -->
        <div>
            <h5>
                About
            </h5>
            <ul class="withoutDot  paddingReset">
                <li>
                    <a href="#" @click.prevent>
                        Masterstudy
                    </a>
                    <span>
                        is Education WordPress theme featured by Learning Management System (LMS) for online education.
                    </span>
                    <div>
                    <span>
                        Developed by 
                    </span>
                    <a href="#" @ck.prevent>
                        StylemixThemes.
                    </a>
                </div>
                </li>
                
                <li class="opacity">
                    <a href="#"  @click.prevent>
                        <i class="fab fa-facebook me-3"></i>
                    </a>
                    <a href="#"  @click.prevent>
                        <i class="fab fa-twitter  me-3"></i>
                    </a>
                    <a href="#"  @click.prevent>
                             
                    <i class="fab fa-instagram fa 2x"></i>
                    </a>
                </li>
                
            </ul>
        </div>
        <!-- Contact -->
        <div>
            <h5>
                Contact
            </h5>
            <ul class="withoutDot paddingReset">
                <li>
                   <span>
                    USA, Callifornia 20, First Avenue, Callifornia
                   </span>
                </li>
                <li>
                    <div>
                        Tel.:+1 212 458 300 32
                    </div>
                    <div>
                       Fax:+1 212 375 24 14
                    </div>
                </li>
                <li class="opacity">
                    <a href="#" @click.prevent class="aGrey">
                        info@masterstudy.com
                    </a>
                </li>
                
            </ul>
        </div>
        <!-- Pages -->
        <div>
            <h5>
                Pages
            </h5>
            <div class="d-flex justify-content-around widthDiv">
                <ul class="widthUl">
                    <li>
                        <a href="#" @click.prevent class="aBlack">
                            Blog
                        </a>
                    </li>
                    <li>
                        <a href="#" @click.prevent class="aBlack">
                            Home
                        </a>
                    </li>
                    <li>
                        <a href="#" @click.prevent class="aBlack">
                            Shortcodes
                        </a>
                    </li>
                    
                </ul>
                <ul class="widthUl">
                    <li>
                        <a href="#" @click.prevent class="aBlack">
                            Courses
                        </a>
                    </li>
                    <li>
                        <a href="#" @click.prevent class="aBlack">
                            Memberships
                        </a>
                    </li>
                    <li>
                        <a href="#" @click.prevent class="aBlack">
                            Typography
                        </a>
                    </li>
                </ul>
            </div>
           
        </div>
        <!-- Blog -->
        <div>
            <h5>
                Blog
            </h5>
            <div class="d-flex align-items-start widthDiv">
                <div>
                    <img src="/public/img/15.jpeg" alt="foto">
                </div>
                
                <div class="height50">
                   <a href="#" @click.prevent class="aBlack">
                        Our main target is to "Developing Yourself as a Leader"
                   </a>
                   <p class="opacity">
                        August 9,2018
                   </p>
                </div>
            </div>
            <div class="d-flex mt-3 widthDiv">
                <div>
                    <img src="/public/img/16.jpeg" alt="foto">
                </div>
                <div class="height50">
                   <a href="#" @click.prevent class="aBlack ">
                        Those Other College Expenses You Aren't Thinking About
                   </a>
                   <p class="opacity">
                         June 3,2015
                   </p> 
                </div>
            </div>
        </div>
    </div>
  </Footer>
</template>



<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

footer{
    height: 300px;
}.withoutDot{
    list-style-type: none;
}a{
    text-decoration: none;
}.paddingReset{
    padding: 0;
}h5{
    margin-bottom: 25px;
}.opacity{
    opacity: 0.5;
}ul li {
    font-size: 0.8rem;
    margin-bottom: 20px;
}ul li, .widthDiv{
    width: 250px;
}li a i  {
    font-size: 1.2rem;
    color: grey
}.aGrey{
    font-size: 0.9rem;
    color: grey;
}.aBlack{
    color: black;
}.widthUl{
    width: 150px;
    padding-left: 20px;
}.widthUl li{
    margin-bottom: 5px;
}.height50{
    height: 50px;
    width: 150px;
    font-size: small;
    margin-left: 10px;
}
</style>
