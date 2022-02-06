<template>
  <body class="antialiased bg-body text-body font-body">
    <div> 
     <!-- <test></test> -->
     <navbar class="fixed"></navbar>
    
      <div>
        <div class="relative font-medium bg-opacity-50 font-heading bg-gray-50">
      
          <div class="fixed top-0 bottom-0 left-0 z-50 hidden w-5/6 max-w-sm navbar-menu">
            <div class="fixed inset-0 bg-gray-800 navbar-backdrop opacity-80"></div>
            <nav class="relative flex flex-col w-full h-full py-8 overflow-y-auto bg-white"><div class="flex items-center pl-16 mb-8">
              <a class="text-2xl font-bold text-gray-800" href="#">
                  <img class="h-12" src="/src/assets/logos/uinel-gray-black.svg" alt=""></a>
              </div>
              <div class="flex items-center px-10 mb-10">
                <a class="flex items-center ml-1" href="#">
                  <img class="ml-6" src="/src/assets/elements/navigations/avatar-online.png" alt=""><img class="ml-6" src="/src/assets/elements/navigations/arrow-down-gray.svg" alt=""></a>
                <a class="ml-auto text-gray-400 hover:text-gray-500" href="#">
                  <svg width="20" height="23" viewbox="0 0 20 23" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M17.5219 18.016H2.70312V8.5933C2.70313 6.719 3.48375 4.92147 4.87328 3.59614C6.2628 2.27081 8.1474 1.52625 10.1125 1.52625C12.0776 1.52625 13.9622 2.27081 15.3517 3.59614C16.7412 4.92147 17.5219 6.719 17.5219 8.5933V18.016Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path><path d="M1 18.0121H19" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path><path d="M8.87891 22H10.8789" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg></a>
              </div>
              <div>
                <ul><li class="px-10 mb-1"><a class="block py-4 pl-8 text-lg rounded-full text-body hover:shadow-2xl" href="#">New tools</a></li>
                  <li class="px-10 mb-1">
                    <a class="flex items-center py-4 pl-8 text-lg rounded-full text-body hover:shadow-2xl" href="#">
                      <span>Products</span>
                      <svg class="ml-4" width="8" height="5" viewbox="0 0 8 5" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M6.97291 0.193232C7.20854 -0.0644107 7.58938 -0.0644107 7.82328 0.193232C8.05804 0.450875 8.05978 0.867141 7.82328 1.12478L4.42529 4.80677C4.19053 5.06441 3.81056 5.06441 3.57406 4.80677L0.176073 1.12478C-0.0586909 0.868102 -0.0586909 0.450875 0.176073 0.193232C0.411706 -0.0644107 0.792544 -0.0644107 1.02644 0.193232L4.00098 3.21284L6.97291 0.193232Z" fill="currentColor"></path></svg></a>
                  </li>
                  <li class="px-10 mb-1"><a class="block py-4 pl-8 text-lg rounded-full text-body hover:shadow-2xl" href="#">Pricing</a></li>
                </ul></div>
              <div class="px-10 mt-auto">
                <button class="w-full px-5 py-3 mt-6 text-sm font-bold tracking-wide uppercase border-2 border-gray-200 border-opacity-50 rounded-full text-body font-body hover:border-gray-300">
                  <span class="block mt-px">New project</span>
                </button>
               
              </div>
            </nav><button class="absolute p-6 navbar-close top-5 right-5">
              <div class="absolute top-3">
                <span class="absolute w-px h-6 transform -rotate-45 bg-black"></span>
                <span class="absolute w-px h-6 transform rotate-45 bg-black"></span>
              </div>
            </button>
          </div>
        </div>
        <section id="home" class="pb-16 overflow-hidden 2xl:pb-20"><div class="relative shadow-gray-900 shadow-2xl bg-gray-100  rounded-b-10xl">
            <div class="container px-4 mx-auto">
              <div class="flex flex-wrap items-center pt-1 pb-20 -mx-4">
                <div class="w-full px-4 mb-24 lg:w-1/2 lg:mb-0">
                  <!-- <span class="block text-sm font-medium tracking-widest text-gray-300 uppercase mb-9">Better communication and work</span> -->
                  <h1  class="max-w-xl mb-16 font-medium leading-none font-heading text-9xl md:text-10xl xl:text-11xl">
                    <span>Hi, it's me <span class="text-blueGray-700 underline">G</span>anpat <span class="text-blueGray-700 underline">J</span>angra and I am a </span>
                    <span class="relative inline-block">
                      <span class="absolute inset-0 xl:-left-8 xl:-right-8">
                        <img class="absolute inset-0 w-full max-w-non" src="/src/assets/elements/heroes/lines-blue1.svg" alt=""><img class="absolute inset-0 w-full mt-1 lg:mt-2 xl:ml-4 max-w-none" src="/src/assets/elements/heroes/lines-blue2.svg" alt="">
                        </span>
                        <!-- full stack -->
                      <span class="relative z-10"> web dev.</span>
                    </span>
                  </h1>
                  <p class="text-xl leading-snug lg:mb-24 text-darkBlueGray-400">Fusce sem lectus, pretium at pellentesque a sagittis non.</p>
                  <div class="flex flex-col sm:flex-row">
                    
                  </div>
                </div>

                <div class="w-full px-4 lg:w-1/2">
                  <div class="relative mx-auto">
                    <!-- <svg class=" absolute rotate-180 h-8 w-60 left-[106px] top-20 text-black"  width="24" height="24" viewBox="0 0 24 24" stroke-width="1" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <line x1="5" y1="12" x2="80" y2="12" />  <line x1="5" y1="12" x2="9" y2="16" />  <line x1="5" y1="12" x2="9" y2="8" /></svg> -->
                    <!-- <h1 class="absolute top-[82px] left-16">Front-End</h1> -->
                    <!-- profile image first circule  -->
                    <div class="w-64 h-64 mx-auto border-4 border-gray-700  rounded-full ">
                    <!-- profile image second circule  -->
                       <div class="w-56 h-56 mx-auto border-4 border-gray-400 rounded-full">
                    <!-- profile image third circule  -->
                          <div class="relative w-48 h-48 mx-auto border-4 rounded-full flex items-center justify-center">
                       <!-- <svg class="mx-auto text-gray-800 h-28"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2" />  <circle cx="12" cy="7" r="4" /></svg> -->
                       <dotlottie-player class="w-[21rem] pb-6 " src="https://assets2.lottiefiles.com/dotlotties/dlf10_sxoye5rr.lottie"  background="transparent"  speed="2"      autoplay></dotlottie-player>
                     
                    <!-- <svg class="absolute  h-8 w-60 left-[54px] top-44 text-gray-400"  width="24" height="24" viewBox="0 0 24 24" stroke-width="1" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <line x1="5" y1="12" x2="80" y2="12" />  <line x1="5" y1="12" x2="9" y2="16" />  <line x1="5" y1="12" x2="9" y2="8" /></svg> -->
                    <!-- <h1 class="text-gray-400 absolute top-[179px] -right-[148px]">Back-End</h1> -->

                      </div> </div>
                    </div>
                    </div>
                </div>
              </div>
            </div>
          </div>
        </section></div>
    <!-- <div class="flex justify-between"> -->
    <!-- skills section  -->
    <h2 id="skills" class="mx-6 font-medium text-9xl md:text-10xl xl:text-11xl font-heading">Skills 
    <span  class=" font-medium text-sm font-heading text-blueGray-700">(MEVN)</span>

    </h2>

    <!-- </div> -->
    <skillsider/>

    <!-- // skills section end  -->
    
    <!-- project section starting  -->
    <project id="project"></project>
    <!-- project section ending  -->

     <!-- home section start -->
    <biography></biography>
         <!-- home section end -->
        
          <!-- contact section start -->
    <contact></contact>
      <!-- contact section end -->
    
     
    
      <section class="font-medium text-white bg-white py-"><div class="container px-4 mx-auto">
          <div class="flex flex-wrap max-w-5xl mx-auto text-center">
            <div class="px-3 mx-auto mb-5">   // lg:mb-0 w-full md:w-1/2 lg:w-1/4
              <div class="bg-indigo-700 rounded-9xl">
                <h2 class="mb-3 font-bold text-9xl">{{dailyvisitor.value}}</h2>
                <h3 class="text-lg leading-6 font-heading">Total Visitor</h3>
              </div>
            </div>
            <!-- <div class="w-full px-3 mb-5 lg:mb-0 md:w-1/2 lg:w-1/4">
              <div class="bg-indigo-700 lg:relative lg:top-14 rounded-9xl">
                <h2 class="mb-3 font-bold text-9xl">4.1K</h2>
                <h3 class="text-lg leading-6 font-heading">monthly</h3>
              </div>
            </div> -->
            <!-- <div class="w-full px-3 mb-5 md:mb-0 lg:mb-0 md:w-1/2 lg:w-1/4">
              <div class="bg-indigo-700 lg:relative lg:top-14 rounded-9xl">
                <h2 class="mb-3 font-bold text-9xl">80</h2>
                <h3 class="text-lg leading-6 font-heading">Countries</h3>
              </div>
            </div> -->
            <!-- <div class="w-full px-3 md:w-1/2 lg:w-1/4">
              <div class="bg-indigo-700 rounded-9xl">
                <h2 class="mb-3 font-bold text-9xl">1m</h2>
                <h3 class="text-lg leading-6 font-heading">avrage time</h3>
              </div>
            </div> -->
          </div>
        </div>
      </section>
    
      <section class="pt-3 pb-8 2xl:pt-8"><div class="container px-4 mx-auto">
          <div class="flex flex-wrap -mx-4 ">
            <div class="w-full px-4 mb-20 lg:w-3/6 lg:mb-0">
              <div class="lg:flex mb-14 xl:mb-16">
                <div class="mb-6 mr-16">
                  <img class="border-[10px] rounded-full" src="/src/assets/images/footers/avatar.png" alt="">
                  </div>
                <div>
                  <!-- <div class="px-12 py-5 mb-3 bg-white max-w-max rounded-2xl shadow-4xl">
                    <h3 class="text-3xl font-bold leading-6">Chilo</h3>
                    <p class="leading-6">How many hours do u need?</p>
                  </div> -->
                  <div class="flex px-8 pt-5 pb-4 ml-6 bg-white max-w-max rounded-2xl shadow-4xl">
                    <div class="w-2 h-2 bg-gray-200 rounded-full animate-bounce animation-1s"></div>
                    <div class="w-2 h-2 mx-2 bg-gray-200 rounded-full animate-bounce animation-2s"></div>
                    <div class="relative w-2 h-2 bg-blue-500 rounded-full animate-bounce animation-1s"></div>
                  </div>
                </div>
              </div>
              <h2 class="max-w-md mb-8 text-6xl font-medium xl:text-8xl font-heading leading-tighter">Have any question? Don’t waste time! Send a message.</h2>
              <!-- <p class="text-xl text-darkBlueGray-400 mb-14 xl:mb-16">Fusce sodales vitae lorem vitae tempus.</p> -->
              <a class="inline-block px-10 py-5 text-xl font-medium leading-6 tracking-tighter text-white bg-blue-500 font-heading hover:bg-blue-600 focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 rounded-xl" href="#">Contact</a>
            </div>
            <div class="w-full px-4 ml-auto lg:w-3/6">
              <div class="flex flex-wrap -mx-4">
                <div class="w-full px-4 mb-24 md:w-auto ">
                  <h3 class="mb-10 text-xl font-medium">pages</h3>
                  <ul><li class="mb-5"><a class="text-darkBlueGray-400 hover:text-darkBlueGray-500" href="#home">Home</a></li>
                    <li class="mb-5"><a class="text-darkBlueGray-400 hover:text-darkBlueGray-500" href="#skills">Skills</a></li>
                    <li class="mb-5"><a class="text-darkBlueGray-400 hover:text-darkBlueGray-500" href="#project">Project</a></li>
                    <li class="mb-5"><a class="text-darkBlueGray-400 hover:text-darkBlueGray-500" href="#contact">Contact</a></li>
                    <!-- <li class="mb-5"><a class="text-darkBlueGray-400 hover:text-darkBlueGray-500" href="#">Founders</a></li> -->
                    <!-- <li><a class=" text-darkBlueGray-400 hover:text-darkBlueGray-500" href="#">Newsroom</a></li> -->
                  </ul>
                  </div>
                 <div class="px-4 mx-auto md:w-auto lg:mb-0">
                  <h3 class="mb-5 text-xl font-medium capitalize">quotes</h3>
                  <ul><li class="text-2xl font-bold text-gray-500 break-words anima font-Leckerli">'' {{quot.content}} ''</li>
                  <li>Author - " <em>{{quot.author}}</em> "</li>
                  </ul></div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    </div>
    <no></no>
  </body>
</template>

<script>
import * as LottiePlayer from '@dotlottie/player-component';
import navbar from '../components/navbar.vue';
import contact from '../components/contact.vue';
import project from '../components/project.vue';
import skillsider from '../components/skillsider.vue';
import  axios from 'axios';
import Navbar from '../components/navbar.vue';
// import Biography from '../components/biography.vue';

export default {

components:{
    
    project,
    navbar,
    skillsider,
    contact,
    Navbar
},

data(){
   return{
        quot:[],
        dailyvisitor:[],
    }
  },
  
    async mounted() {
      let result= await axios.get("https://api.quotable.io/random");
      // console.log(result);
     this.quot=result.data;
    //  console.log(this.quot);
let daily= await axios.get("https://api.countapi.xyz/hit/myresume");

// console.log(daily.data.value);
this.dailyvisitor=daily.data

    },

}
</script>
<style>
body {
  scroll-behavior: smooth;
}
.slide-enter-active {
  animation: menu-slide 5s;
}
.slide-leave-active {
  animation: menu-slide 5s reverse;
}
@keyframes menu-slide {
  from {
    transform: translateX(-100%);
  }
  to {
    transform: translateX(0);
  }
}
  
</style>