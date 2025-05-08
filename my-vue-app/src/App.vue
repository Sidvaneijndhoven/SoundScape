<!-- 
  Made by: Sid van Eijndhoven
  Date: 8-5-2025
  File: App.vue
  Description: One page website
-->
<template>
  <div class="main">
    <div class="bg-gray-800  flex flex-col justify-between">
      <div class="flex items-center justify-between px-4 py-6 bg-gray-900 text-white">
        <h1 class="text-2xl font-bold">&copy; Soundscape</h1>
        <nav class="space-x-4">
          <a href="#calander" class="hover:text-gray-300 text-2xl">Login 🔐</a>
        </nav>
      </div>
    </div>

    <!-- Logo -->
    <img src="./assets/media/logo.jpg" alt="House" class="w-1/6 h-1/6 object-cover m-0 p-0 mx-auto mb-50 mt-20" id="SmallTransform" ref="logo"/>
    
    <section>
      <div class="devider flex items-center">
        <span class="h-px flex-1 bg-gradient-to-r from-transparent to-gray-300"></span>
        <div class="shrink-0 px-4 text-gray-900">🎧🎙️🎧</div>
        <span class="h-px flex-1 bg-gradient-to-l from-transparent to-gray-300"></span>
      </div>
      
      <div class="mx-auto max-w-screen-xl px-4 py-8 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 gap-4 md:grid-cols-4 md:items-center md:gap-8">
          <div class="md:col-span-1">
            <div class="max-w-lg md:max-w-none">
              <h2 class="text-2xl font-semibold text-gray-900 sm:text-3xl">
                Escape Into Sound: A Journey Through Tranquil Soundscapes
              </h2>
              <p class="mt-4 text-gray-700">
                Step away from the chaos of everyday life and immerse yourself in the calming embrace of sound. From nature’s whispers to ambient melodies, each track is crafted to help you relax, focus, or simply unwind. Let the rhythm of the world guide you to a peaceful state of mind. Perfect for work, meditation, or moments of stillness, discover your own sanctuary in every sound.
              </p>
            </div>
          </div>
          <div class="md:col-span-3">
            <img
              src="./assets/media/header.jpg"
              class="rounded"
              alt=""
              id="SmallTransform"
              ref="HeaderAnimation"
            />  
          </div>
        </div>
        
        <button class="text-center rounded border-1 p-2 w-1/5" id="SmallTransform" ref="StartListening" @click="WorkInProgress">
          Start Listening
        </button>
      </div>
    </section>

    <!-- Blogcards -->
    <!-- Blog Card 1 -->
    <div class="devider flex items-center mt-75">
      <span class="h-px flex-1 bg-gradient-to-r from-transparent to-gray-300"></span>
      <div class="shrink-0 px-4 text-gray-900">🎧🎙️🎧</div>
      <span class="h-px flex-1 bg-gradient-to-l from-transparent to-gray-300"></span>
    </div>

    <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 lg:gap-8 mt-20 mb-100">
      <div class="h-32 rounded" id="SmallTransform">
        <article class="overflow-hidden rounded-lg border-2 border-gray-100 bg-gray-800 shadow-xs w-4/5 mx-auto" ref="Blogcard1Animation">
          <img
            alt=""
            src="./assets/media/discover.png"
            class="h-56 w-full object-cover"
          />
          <div class="p-4 sm:p-6">
            <a href="#">
              <h3 class="text-lg font-medium text-gray-900">
                 Your Beat on Music News & Events
              </h3>
            </a>
            <p class="mt-2 line-clamp-3 text-sm/relaxed text-gray-500">
              Dive into Soundscape — your go-to hub for the latest music news, artist spotlights, album drops, and live event coverage. From local scenes to global stages, we bring the rhythm of the music world straight to you.
            </p>
            <a href="#calander" class="group mt-4 inline-flex items-center gap-1 text-sm font-medium text-blue-600">
              Find out more
              <span aria-hidden="true" class="block transition-all group-hover:ms-0.5 rtl:rotate-180">
                &rarr;
              </span>
            </a>
          </div>
        </article>
      </div>

      <div class="h-32 rounded" id="SmallTransform">
        <!-- Blogcard 2 -->
        <article class="overflow-hidden rounded-lg border-2 border-gray-100 bg-gray-800 shadow-xs w-4/5 mx-auto" ref="Blogcard2Animation" id="Transform">
          <img
            alt=""
            src="./assets/media/blogCard.jpg"
            class="h-56 w-full object-cover"
          />
          <div class="p-4 sm:p-6">
            <a href="#">
              <h3 class="text-lg font-medium text-gray-900">
                Soundscape: Where Music Lives & Events Come Alive
              </h3>
            </a>
            <p class="mt-2 line-clamp-3 text-sm/relaxed text-gray-500">
              Discover breaking music news, buzzing event updates, and behind-the-scenes stories — all in one place. Soundscape is your backstage pass to everything happening in the world of music.
            </p>
            <a href="#calander" class="group mt-4 inline-flex items-center gap-1 text-sm font-medium text-blue-600">
              Find out more
              <span aria-hidden="true" class="block transition-all group-hover:ms-0.5 rtl:rotate-180">
                &rarr;
              </span>
            </a>
          </div>
        </article>
      </div>
    </div>  

    <div class="devider flex items-center my-25">
      <span class="h-px flex-1 bg-gradient-to-r from-transparent to-gray-300"></span>
      <div class="shrink-0 px-4 text-gray-900">🎧🎙️🎧</div>
      <span class="h-px flex-1 bg-gradient-to-l from-transparent to-gray-300"></span>
    </div>

    <!-- Events tab -->
    <div class="events">
      <div class="AboutEvent min-h-screen w-full flex flex-col justify-center items-center bg-gray-800 mb-20">
        <img src="./assets/media/Tomorrowland.jpg" alt="House" class="w-3/5 h-auto object-cover m-10 p-0 mx-auto rounded-2xl " id="SmallBoxTransform">
        <!-- w-11/12 of the width of parent container lg is a responsiveness -->
        <p class="text-center w-11/12 lg:w-1/2 text-2xl mb-20">
          Experience immersive sound events with live performances and interactive installations that inspire creativity and relaxation.
        </p>
      </div>

      <!-- Grid responsive -->
      <div class="relative w-full">
        <img src="./assets/media/soundback.png" class="w-2/5 h-1/4 object-cover mx-auto rounded" id="SmallTransform">
        <p class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center text-4xl mb-15" style=" font-family: fantasy;">
          3<br> 🎙 most popular upcoming events 🎙
        </p>
      </div>

      <div class="grid grid-cols-1 gap-4 lg:grid-cols-3 lg:gap-2 ">  
        <div class="h-auto rounded">
          <img src="./assets/media/EventPoster1.png" alt="House" class="w-auto h-4/6 object-cover m-0 p-0 mx-auto rounded" id="SmallBoxTransform" ref="card1Animation">
        </div>
        <div class="h-auto rounded">
          <img src="./assets/media/EventPoster2.png" alt="House" class="w-auto h-4/6 object-cover m-0 p-0 mx-auto rounded" id="SmallBoxTransform" ref="card3Animation">
        </div>
        <div class="h-auto rounded">
          <img src="./assets/media/EventPoster3.png" alt="House" class="w-auto h-4/6 object-cover m-0 p-0 mx-auto rounded" id="SmallBoxTransform" ref="card2Animation">
        </div>
      </div>
    </div>
    <!-- Event calander -->
    <div class="relative w-full" id="calander">
        <img src="./assets/media/soundback.png" class="w-2/5 h-1/4 object-cover mx-auto rounded" id="SmallTransform">
        <p class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center text-4xl mb-15" style=" font-family: fantasy;">
         🎶 Upcoming events 🎙
        </p>
      </div>
    <div class="overflow-x-auto w-90% mx-auto p-10">
      <table class="min-w-full bg-gray-500 border-collapse border rounded-2xl border-gray-800 mb-20" ref="tableAnimation">
        <thead>
          <tr class="bg-gray-600">
            <th class="p-4 text-left text-sm font-semibold text-gray-700">Event</th>
            <th class="p-4 text-left text-sm font-semibold text-gray-700">Date</th>
            <th class="p-4 text-left text-sm font-semibold text-gray-700">Price</th>
            <th class="p-4 text-left text-sm font-semibold text-gray-700">Location</th>
            <th class="p-4 text-left text-sm font-semibold text-gray-700"></th> 
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="p-4">Tomorrowland</td>
            <td class="p-4">20-07-2025</td>
            <td class="p-4">€200</td>
            <td class="p-4">Boom, Belgium</td>
            <td class="p-4">
              <button class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700 cursor-pointer" @click="bookNow">Book Now!</button>
            </td>
          </tr>
          <tr>
            <td class="p-4">Coachella</td>
            <td class="p-4">12-04-2025</td>
            <td class="p-4">$500</td>
            <td class="p-4">Indio, California</td>
            <td class="p-4">
              <button class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700 cursor-pointer" @click="bookNow">Book Now!</button>
            </td>
          </tr>
          <tr>
            <td class="p-4">Glastonbury</td>
            <td class="p-4">26-06-2025</td>
            <td class="p-4">£250</td>
            <td class="p-4">Pilton, England</td>
            <td class="p-4">
              <button class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700 cursor-pointer" @click="bookNow">Book Now!</button>
            </td>
          </tr>
          <tr>
            <td class="p-4">Lollapalooza</td>
            <td class="p-4">01-08-2025</td>
            <td class="p-4">$300</td>
            <td class="p-4">Chicago, Illinois</td>
            <td class="p-4">
              <button class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700 cursor-pointer" @click="bookNow">Book Now!</button>
            </td>
          </tr>
          <tr>
            <td class="p-4">Ultra Music Festival</td>
            <td class="p-4">20-03-2025</td>
            <td class="p-4">$400</td>
            <td class="p-4">Miami, Florida</td>
            <td class="p-4">
              <button class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-700 cursor-pointer" @click="bookNow">Book Now!</button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
   <Footer></Footer>
  </div>
</template>

<script setup> 
import Footer from './components/Footer.vue'
import { onMounted, ref } from "vue";
import { animate } from "motion";
import { useIntersectionObserver } from "@vueuse/core";
import { useToast } from 'vue-toastification'

const toast = useToast()

function bookNow() {
  toast.success('✅ Booking added to profile! check your profile for more information')
}

function WorkInProgress() {
  toast.error('🚧 This is still in development!')
}

const logo = ref(null);
const StartListening = ref(null);
const HeaderAnimation = ref(null);
const Blogcard1Animation = ref(null);
const Blogcard2Animation = ref(null);
const card1Animation = ref(null);
const card2Animation = ref(null);
const card3Animation = ref(null);
const tableAnimation = ref(null);

// om de animatie te laten zien\
// table animation
useIntersectionObserver(tableAnimation, ([{ isIntersecting }]) => {
    if (isIntersecting) {
      animate(tableAnimation.value, 
        { 
          opacity: [0, 1], 
          scale: [0.8, 1], 
          y: [200, 0]           
        }, 
        { 
          duration: 1, 
          easing: "ease-in"    
        }
      );
    }
  });

// Blogcard animation
useIntersectionObserver(Blogcard1Animation, ([{ isIntersecting }]) => {
    if (isIntersecting) {
      animate(Blogcard1Animation.value, 
        { 
          opacity: [0, 1], 
          scale: [0.8, 1], 
          x: [-200, 0]           
        }, 
        { 
          duration: 1, 
          easing: "ease-in"    
        }
      );
    }
  });

useIntersectionObserver(Blogcard2Animation, ([{ isIntersecting }]) => {
    if (isIntersecting) {
      animate(Blogcard2Animation.value, 
        { 
          opacity: [0, 1],  
          scale: [0.8, 1], 
          x: [200, 0]           
        }, 
        { 
          duration: 1, 
          easing: "ease-in"    
        }
      );
    }
  });

// Event card animation
useIntersectionObserver(card1Animation, ([{ isIntersecting }]) => {
    if (isIntersecting) {
      animate(card1Animation.value, 
        { 
          opacity: [0, 1],  
          scale: [0.8, 1], 
          x: [200, 0]           
        }, 
        { 
          duration: 1, 
          easing: "ease-in"    
        }
      );
    }
  });

useIntersectionObserver(card2Animation, ([{ isIntersecting }]) => {
  if (isIntersecting) {
    animate(card2Animation.value, 
      { 
        opacity: [0, 1],  
        scale: [0.8, 1], 
        x: [-200, 0]           
      }, 
      { 
        duration: 1, 
        easing: "ease-in"    
      }
    );
  }
});


useIntersectionObserver(card3Animation, ([{ isIntersecting }]) => {
  if (isIntersecting) {
    animate(card3Animation.value, 
      { 
        opacity: [0, 1],  
        scale: [0.8, 1], 
      }, 
      { 
        duration: 1, 
        easing: "ease-in"    
      }
    );
  }
});

// Header animation
useIntersectionObserver(StartListening, ([{ isIntersecting }]) => {
    if (isIntersecting) {
      animate(StartListening.value, 
        { 
          opacity: [0, 1], 
          scale: [0.8, 1], 
          x: [-200, 0]           
        }, 
        { 
          duration: 1, 
          easing: "ease-in"    
        }
      );
    }
  });

useIntersectionObserver(HeaderAnimation, ([{ isIntersecting }]) => {
  if (isIntersecting) {
    animate(HeaderAnimation.value, { opacity: [0, 1], scale: [0.8, 1] }, { duration: 1, easing: "ease-out" });
  }
});
// Logo animatie
useIntersectionObserver(logo, ([{ isIntersecting }]) => {
    if (isIntersecting) {
      animate(logo.value, 
        { 
          opacity: [0, 1], 
          scale: [0.8, 1], 
          rotate: [0, 360],      
          x: [-700, 0]           
        }, 
        { 
          duration: 1.5, 
          easing: "ease-out"    
        }
      );
    }
  });
</script>