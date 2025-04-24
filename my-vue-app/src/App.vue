<template>
  <div class="main">
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
        <div class="md:col-span-3" >
          <img
            src="./assets/media/header.jpg"
            class="rounded"
            alt=""
            id="SmallTransform"
            ref="HeaderAnimation"
          />  
        </div>
      </div>
      <button class="text-center rounded border-1 p-2 w-1/5" id="SmallTransform" ref="StartListening">
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
    <div class="grid grid-cols-1 gap-4 lg:grid-cols-2 lg:gap-8 mt-20 mb-200">
      <div class="h-32 rounded bg-gray-300" id="SmallTransform">
        <article class="overflow-hidden rounded-lg border-2 border-gray-100 bg-white shadow-xs w-4/5 mx-auto" ref="Blogcard1Animation">
          <img
            alt=""
            src="./assets/media/discover.png"
            class="h-56 w-full object-cover"
          />
          <div class="p-4 sm:p-6">
            <a href="#">
              <h3 class="text-lg font-medium text-gray-900">
                The Art of Sound Design: Crafting the Perfect Atmosphere
              </h3>
            </a>
            <p class="mt-2 line-clamp-3 text-sm/relaxed text-gray-500">
              Explore the creative process behind crafting immersive soundscapes. Learn how sound designers use a combination of techniques and tools to create realistic, atmospheric audio experiences that transport you to new worlds.  
            </p>
            <a href="#" class="group mt-4 inline-flex items-center gap-1 text-sm font-medium text-blue-600">
              Find out more
              <span aria-hidden="true" class="block transition-all group-hover:ms-0.5 rtl:rotate-180">
                &rarr;
              </span>
            </a>
            </div>
        </article>
      </div>
      <div class="h-32 rounded bg-gray-300" id="SmallTransform">
        <!-- Blogcard 2 -->
        <article class="overflow-hidden rounded-lg border-2 border-gray-100 bg-white shadow-xs w-4/5 mx-auto" ref="Blogcard2Animation" id="Transform">
          <img
            alt=""
            src="./assets/media/blogCard.jpg"
            class="h-56 w-full object-cover"
          />
          <div class="p-4 sm:p-6">
            <a href="#">
              <h3 class="text-lg font-medium text-gray-900">
                The Science of Sound: How Music Can Enhance Your Mood
              </h3>
            </a>
            <p class="mt-2 line-clamp-3 text-sm/relaxed text-gray-500">
              Dive into the fascinating world of sound science. Discover how different frequencies and melodies can influence your emotions, boost productivity, and even improve your mental health. Learn how the right sound can transform your day.
            </p>
            <a href="#" class="group mt-4 inline-flex items-center gap-1 text-sm font-medium text-blue-600">
              Find out more
              <span aria-hidden="true" class="block transition-all group-hover:ms-0.5 rtl:rotate-180">
                &rarr;
              </span>
            </a>
            </div>
        </article>
      </div>
    </div>  
    <div class="devider flex items-center mt-75">
        <span class="h-px flex-1 bg-gradient-to-r from-transparent to-gray-300"></span>
        <div class="shrink-0 px-4 text-gray-900">🎧🎙️🎧</div>
        <span class="h-px flex-1 bg-gradient-to-l from-transparent to-gray-300"></span>
    </div>
    <!-- Events tab -->
    <div class="events">
      <div class="AboutEvent min-h-screen w-full flex flex-col justify-center items-center">
        <img src="./assets/media/Tomorrowland.jpg" alt="House" class="w-3/5 h-auto object-cover m-10 p-0 mx-auto rounded-2xl" id="SmallBoxTransform">
        <!-- w-11/12 of the width of parent container lg is a responsiveness -->
        <p class="text-center w-11/12 lg:w-1/2 text-2xl mb-20">
          Experience immersive sound events with live performances and interactive installations that inspire creativity and relaxation.
        </p>
        <p class="text-center w-11/12 lg:w-1/2 text-2xl mb-10">
          Upcomming events include:
        </p>
      </div>
      <!-- Grid responsive -->
      <div class="grid grid-cols-1 gap-4 lg:grid-cols-3 lg:gap-8 ">  
        <div class="h-auto rounded bg-gray-300">
          <img src="./assets/media/EventPoster1.png" alt="House" class="w-auto h-3/4 object-cover m-0 p-0 mx-auto rounded" id="SmallBoxTransform">
        </div>
        <div class="h-auto rounded bg-gray-300">
          <img src="./assets/media/EventPoster2.png" alt="House" class="w-auto h-3/4 object-cover m-0 p-0 mx-auto rounded" id="SmallBoxTransform">
        </div>
        <div class="h-auto rounded bg-gray-300">
          <img src="./assets/media/EventPoster3.png" alt="House" class="w-auto h-3/4 object-cover m-0 p-0 mx-auto rounded" id="SmallBoxTransform">
        </div>
      </div>
    </div>
    <Footer class="mt-auto"></Footer>  
  </div>
</template>
  
<script setup> 
import Footer from './components/Footer.vue'
import { onMounted, ref } from "vue";
import { animate } from "motion";
import { useIntersectionObserver } from "@vueuse/core";



const logo = ref(null);
const StartListening = ref(null);
const HeaderAnimation = ref(null);
const Blogcard1Animation = ref(null);
const Blogcard2Animation = ref(null);

// om de animatie te laten zien
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