<template>
 <section class="bg-white xl:pt-20"><div class="container px-4 mx-auto">
          <div class="relative flex flex-wrap -mx-4">
            <div class="w-full px-4 lg:w-1/2">
              <div class="text-center">
                <h2 class="mb-20 font-medium xl:mt-8 xl:mb-16 text-9xl md:text-10xl xl:text-11xl font-heading">Projects</h2>
              </div>
              <div class="flex flex-wrap justify-center mb-20 -mx-1 xl:flex-nowrap lg:px-10">

 <swiper 
     
        :spaceBetween="10"
        :pagination="true"
         :modules="modules"
        :thumbs="{ swiper: thumbsSwiper }"
        class="mx-10 mySwiper2"
    >

        <swiper-slide>

                <div class="w-full px-1 mb-4 xl:w-auto xl:mb-0 ">
                  <div class="px-6 pt-10 pb-12 text-center bg-gray-50 rounded-7xl shadow-gray-300 shadow-sm mb-10">
                    <img class="w-20 h-20 mx-auto mb-5" src="/src/assets/images/team/placeholder-photo.png" alt=""><h4 class="mb-12 text-xl font-medium font-heading">Ainsley Stones</h4>
                    <span class="p-2 text-sm font-bold text-gray-500 shadow-blueGray-900 shadow-inner uppercase bg-white rounded-full">Founder</span>
                  </div>
                </div>
        </swiper-slide>

        <swiper-slide>

                <div class="relative w-full px-1 mb-4 xl:w-auto xl:mb-0">
                  <div class="px-6 pt-10 pb-12 text-center bg-gray-50 rounded-7xl shadow-gray-300 shadow-sm">
                    <img class="w-20 h-20 mx-auto mb-5" src="/src/assets/images/team/placeholder-photo.png" alt=""><h4 class="mb-12 text-xl font-medium font-heading">Faustina H. Fawn</h4>
                    <span class="p-2 text-sm font-bold text-gray-500 shadow-blueGray-900 shadow-inner uppercase bg-white rounded-full">Manager</span>
                  </div>
                </div>
        </swiper-slide>

        <swiper-slide>

                <div class="w-full px-1 mb-4 xl:w-auto xl:mb-0">
                  <div class="px-6 pt-10 pb-12 text-center bg-gray-50 rounded-7xl shadow-gray-300 shadow-sm">
                    <img class="w-20 h-20 mx-auto mb-5" src="/src/assets/images/team/placeholder-photo.png" alt=""><h4 class="mb-12 text-xl font-medium font-heading">Jasmine Joy</h4>
                    <span class="p-2 text-sm font-bold text-gray-500 shadow-blueGray-900 shadow-inner uppercase bg-white rounded-full">Manager</span>
                  </div>
                </div>
            
        </swiper-slide>

</swiper>
 </div> 
  </div>





            <img class="absolute top-0 hidden transform translate-x-1/2 xl:block left-1/2" src="/src/assets/images/team/dots.svg" alt="">

            <div class="w-full px-4 lg:w-1/2 ">
              <div class="text-center lg:px-10 md:mb-16">
                <h2 class="mt-8 font-medium text-9xl md:text-10xl xl:text-11xl font-heading">Details</h2>
               <swiper
        @swiper="setThumbsSwiper"
        :spaceBetween="10"
        :slidesPerView="1"
        :freeMode="false"
       
        :watchSlidesProgress="true"
        class="mx-5 mySwiper"
    >

     <swiper-slide>
                <img class="block mx-auto mb-12" src="/src/assets/images/team/dots2.svg" alt="">
                <div class="flex items-start mb-10">
                  <img class="rotate-180" src="/src/assets/images/team/quote.png" alt="">
                  <div class="max-w-sm mx-auto text-justify -mt-9 ">
                    <p class="text-2xl font-medium mx-2">Morbi ut nisl placerat, suscipit urna non, fringilla leo. Aenean mi libero, pretium eu convallis non, feugiat non ipsum. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia!</p>
                  </div>
                  <img src="/src/assets/images/team/quote.png" alt="">
                  </div>
</swiper-slide>
     <swiper-slide>
                <img class="block mx-auto mb-12" src="/src/assets/images/team/dots2.svg" alt="">
                <div class="flex items-start mb-10">
                  <img class="rotate-180" src="/src/assets/images/team/quote.png" alt="">
                  <div class="max-w-sm mx-auto text-justify -mt-9">
                    <p class="text-2xl font-medium mx-2">Morbi ut nisl placerat, suscipit urna non, fringilla leo. Aenean mi libero, pretium eu convallis non, feugiat non ipsum. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia!</p>
                  </div>
                  <img src="/src/assets/images/team/quote.png" alt="">
                  </div>
</swiper-slide>
     <swiper-slide>
                <img class="block mx-auto mb-12" src="/src/assets/images/team/dots2.svg" alt="">
                <div class="flex items-start mb-10">
                  <img class="rotate-180" src="/src/assets/images/team/quote.png" alt="">
                  <div class="max-w-sm mx-auto text-justify -mt-9">
                    <p class="text-2xl font-medium mx-2">Morbi ut nisl placerat, suscipit urna non, fringilla leo. Aenean mi libero, pretium eu convallis non, feugiat non ipsum. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia!</p>
                  </div>
                  <img src="/src/assets/images/team/quote.png" alt="">
                  </div>
</swiper-slide>

 </swiper>
                <div class="flex items-center justify-center -mx-4">
              
                
                 
                </div>
              </div>
              <div class="hidden h-1 md:block">
                <div class="w-64 mx-auto bg-gray-100 rounded-full h-1/2">
                  <div class="w-1/3 h-full bg-purple-500 rounded-full"></div>
                </div>
              </div>
            </div>



          </div>
        </div>
      </section>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";
import "swiper/css/pagination"
import "swiper/css/free-mode";
import "swiper/css/navigation";
import "swiper/css/thumbs";

// import "./style.css";

// import Swiper core and required modules
import SwiperCore, { FreeMode, Navigation, Thumbs,Pagination } from "swiper";

// install Swiper modules
SwiperCore.use([FreeMode, Navigation, Thumbs,Pagination]);

export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    data() {
        return {
            thumbsSwiper: null,
            
        };
    },
    methods: {
        setThumbsSwiper(swiper) {
            this.thumbsSwiper = swiper;
        },
    },
};
</script>

<style>
.swiper-pagination-bullet{
  background: #ed0808;
  opacity: 1;
}
.swiper-pagination-bullet-active{
  /* color: red; */
  height: 13px;
  width: 13px;
  background: #ed0808;
}
</style>