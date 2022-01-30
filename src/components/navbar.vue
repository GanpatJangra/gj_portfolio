<template>
     <section class="relative font-medium bg-gray-100 font-heading">
        <nav class="flex justify-between px-6 lg:px-12">
          <div class=" mx-auto">
         
<lottie-player class="w-28 animate-slide-left " src="https://assets8.lottiefiles.com/packages/lf20_dUbSb3.json"  background="transparent"  speed="1"  loop  autoplay></lottie-player>
              <!-- <img class=" w-14 p-2 animate-slide-left border-2 rounded-full  " src="/src/assets/dog.png" alt="dog"> -->
                      
          </div>
          <button @click="hidden=!hidden" class="self-center xl:hidden text-body focus:outline-none active:border-2 border-yellow-600 px-3 py-3 rounded-md">
            <svg width="25" height="16" viewbox="0 0 25 16" fill="none" xmlns="http://www.w3.org/2000/svg"><rect width="25" height="2" fill="currentColor"></rect><rect y="14" width="25" height="2" fill="currentColor"></rect></svg>
          </button>
        </nav>
<transition name="slide">
        <div :class="{hidden}"  class="fixed top-0 bottom-0 left-0 z-50 w-5/6 max-w-sm ">
          <div class="fixed inset-0 bg-gray-800 navbar-backdrop opacity-80"></div>
          <nav class="relative flex flex-col w-full h-full py-8 overflow-y-auto bg-white">
            <div class="flex items-center pl-16 mb-8">
              <a class="text-2xl font-bold text-gray-800" href="#">
                <!-- <img class="h-12" src="/src/assets/logos/uinel-gray-black.svg" alt=""> -->
                <h1>Ganpat Jangra</h1>
              </a>
            </div>
            <div class="flex items-center px-10 mb-10">
              <a class="flex items-center ml-1" href="#">
                <img class="ml-6 rounded-full" src="https://picsum.photos/50/50" alt="">
              </a>
              <div class="ml-auto text-gray-400 hover:text-gray-500">
                <svg width="20" height="23" viewbox="0 0 20 23" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M17.5219 18.016H2.70312V8.5933C2.70313 6.719 3.48375 4.92147 4.87328 3.59614C6.2628 2.27081 8.1474 1.52625 10.1125 1.52625C12.0776 1.52625 13.9622 2.27081 15.3517 3.59614C16.7412 4.92147 17.5219 6.719 17.5219 8.5933V18.016Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                  <path d="M1 18.0121H19" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                  <path d="M8.87891 22H10.8789" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                </svg>
              </div>
            </div>
            <div>  
              <ul>
              
                <li class="px-10 mb-1"><a class="block py-4 pl-8 text-lg rounded-full text-body hover:shadow-2xl border shadow-black" href="#home">Home</a></li>
                <li class="px-10 mb-1"><a class="block py-4 pl-8 text-lg rounded-full text-body hover:shadow-2xl border shadow-black" href="#skills">Skills</a></li>
                <li class="px-10 mb-1"><a class="block py-4 pl-8 text-lg rounded-full text-body hover:shadow-2xl border shadow-black" href="#contact">Contact</a></li>
                <li class="px-10 mb-1"><a class="block py-4 pl-8 text-lg rounded-full text-body hover:shadow-2xl border shadow-black" href="#project">Project</a></li>
              <button @click="hidden=!hidden" class="absolute p-6 right-5">
            <div class="absolute top-3">
              <span class="absolute w-px h-6 transform -rotate-45 bg-black"></span>
              <span class="absolute w-px h-6 transform rotate-45 bg-black"></span>
            </div>
          </button>
                
              </ul>
            </div>
            <div class="px-10 mt-auto">
              <button class="w-full px-5 py-3 mt-6 text-sm font-bold tracking-wide uppercase border-2 border-gray-200 border-opacity-50 rounded-full font-body hover:border-gray-300">
                <span class="block mt-px text-black">New project</span>
              </button>
            
            </div>
          </nav>
          <button @click="hidden=!hidden" class="absolute p-6 top-5 right-5">
            <div class="absolute top-3">
              <span class="absolute w-px h-6 transform -rotate-45 bg-black"></span>
              <span class="absolute w-px h-6 transform rotate-45 bg-black"></span>
            </div>
          </button>
        </div>
</transition>
      </section>
</template>


<script>
import "https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js";
// import * as LottiePlayer from '@dotlottie/player-component';

export default {

// name:nav,

data(){
   return{
        hidden:true,
     
      
    }
  },
}
</script>