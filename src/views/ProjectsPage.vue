<template>
  <NavBar class="bg-gray-900 text-gray-200"/>
  <div class="p-6 max-w-7xl mx-auto">
    <h1 class="text-xl font-bold">Projects</h1>
    <p class="leading-relaxed text-gray-700 mt-4">
      Here are some of the projects I've built across embedded systems and web development:
    </p>
    
    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-12 mt-8">
      <!-- Project 1 -->
      <div class="bg-gray-100 rounded-xl overflow-hidden border border-gray-300">
        <img src="../assets/imgs/chess.png" alt="Chessboard" class="w-full h-40 object-cover">
        <div class="p-5">
          <div class="flex items-center gap-3 mb-2">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-5">
              <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 3v1.5M4.5 8.25H3m18 0h-1.5M4.5 12H3m18 0h-1.5m-15 3.75H3m18 0h-1.5M8.25 19.5V21M12 3v1.5m0 15V21m3.75-18v1.5m0 15V21m-9-1.5h10.5a2.25 2.25 0 0 0 2.25-2.25V6.75a2.25 2.25 0 0 0-2.25-2.25H6.75A2.25 2.25 0 0 0 4.5 6.75v10.5a2.25 2.25 0 0 0 2.25 2.25Zm.75-12h9v9h-9v-9Z" />
            </svg>
            <h3 class="font-semibold">Chess Engine</h3>
          </div>
          <p class="text-gray-700 mb-4">
            A chess bot built with Python, it uses alpha-beta pruning for move selection and a simple evaluation function. It can play against human opponents or other bots.
          </p>
          <div class="flex flex-wrap gap-2 mb-4 justify-center text-xs font-medium">
            <span class="px-3 py-1 rounded-full text-orange-800 border border-orange-400">
              Python
            </span>
            <span class="px-3 py-1 rounded-full text-green-800 border border-green-400">
              AI
            </span>
            <span class="px-3 py-1 rounded-full text-blue-800 border border-blue-400">
              Chess
            </span>
            <span class="px-3 py-1 rounded-full text-gray-900 border border-gray-500">
              Minimax
            </span>
          </div>
          <a href="https://github.com/mvntando/dorse" target="_blank" class="inline-flex items-center gap-1 mt-3 text-sm font-medium text-gray-700 hover:text-black decoration-gray-600 hover:decoration-gray-700 underline underline-offset-4 transition">
            View on GitHub
            <span aria-hidden="true">↗</span>
          </a>
        </div>
      </div>

      <!-- Project 2 -->
      <div class="bg-gray-100 rounded-xl overflow-hidden  border border-gray-300">
        <img src="../assets/imgs/weather.png" alt="Weather App" class="w-full h-40 object-cover">
        <div class="p-5">
          <div class="flex items-center gap-3 mb-2">
            <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="size-5" viewBox="0 0 16 16">
              <path d="M7 8a3.5 3.5 0 0 1 3.5 3.555.5.5 0 0 0 .624.492A1.503 1.503 0 0 1 13 13.5a1.5 1.5 0 0 1-1.5 1.5H3a2 2 0 1 1 .1-3.998.5.5 0 0 0 .51-.375A3.5 3.5 0 0 1 7 8m4.473 3a4.5 4.5 0 0 0-8.72-.99A3 3 0 0 0 3 16h8.5a2.5 2.5 0 0 0 0-5z"/>
              <path d="M10.5 1.5a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0zm3.743 1.964a.5.5 0 1 0-.707-.707l-.708.707a.5.5 0 0 0 .708.708zm-7.779-.707a.5.5 0 0 0-.707.707l.707.708a.5.5 0 1 0 .708-.708zm1.734 3.374a2 2 0 1 1 3.296 2.198q.3.423.516.898a3 3 0 1 0-4.84-3.225q.529.017 1.028.129m4.484 4.074c.6.215 1.125.59 1.522 1.072a.5.5 0 0 0 .039-.742l-.707-.707a.5.5 0 0 0-.854.377M14.5 6.5a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1z"/>
            </svg>
            <h3 class="font-semibold">Weather App</h3>
          </div>
          <p class="text-gray-700 mb-4">
            Flask web app that displays real-time weather data from OpenWeatherMap. Features city search, responsive UI, and simple REST API integration.
          </p>
          <div class="flex flex-wrap gap-2 mb-4 justify-center text-xs font-medium">
            <span class="px-3 py-1 rounded-full  text-green-800 border border-green-400">
              Flask
            </span>
            <span class="px-3 py-1 rounded-full text-gray-900 border border-gray-500">
              Python
            </span>
            <span class="px-3 py-1 rounded-full  text-orange-800 border border-orange-400">
              REST API
            </span>
            <span class="px-3 py-1 rounded-full  text-blue-800 border border-blue-400">
              SQLite3
            </span>
          </div>
          <a href="https://weather50.vercel.app" target="_blank" class="inline-flex items-center gap-1 mt-3 text-sm font-medium text-gray-700 hover:text-black decoration-gray-600 hover:decoration-gray-700 underline underline-offset-4 transition">
            View Live Demo
            <span aria-hidden="true">↗</span>
          </a>
        </div>
      </div>

      <!-- Project 3 -->
      <div class="bg-gray-100 rounded-xl overflow-hidden  border border-gray-300">
        <img src="../assets/imgs/lo-ra.jpg" alt="Weather App" class="w-full h-40 object-cover">
        <div class="p-5">
          <div class="flex items-center gap-3 mb-2">
            <svg fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-5">
              <path stroke-linecap="round" stroke-linejoin="round" d="M13.19 8.688a4.5 4.5 0 0 1 1.242 7.244l-4.5 4.5a4.5 4.5 0 0 1-6.364-6.364l1.757-1.757m13.35-.622 1.757-1.757a4.5 4.5 0 0 0-6.364-6.364l-4.5 4.5a4.5 4.5 0 0 0 1.242 7.244" />
            </svg>
            <h3 class="font-semibold">LoRa App</h3>
          </div>
          <p class="text-gray-700 mb-4">
            Vue 3 dashboard for monitoring LoRa sensor nodes. Streams live sensor values from Firestore, raises alerts when thresholds are crossed, and shows per-node historical charts.
          </p>
          <div class="flex flex-wrap gap-2 mb-4 justify-center text-xs font-medium">
            <span class="px-3 py-1 rounded-full text-gray-900 border border-gray-500">
              Firebase
            </span>
            <span class="px-3 py-1 rounded-full  text-green-800 border border-green-400">
              Vue 3
            </span>
            <span class="px-3 py-1 rounded-full  text-blue-800 border border-blue-400">
              ESP32
            </span>
            <span class="px-3 py-1 rounded-full  text-orange-800 border border-orange-400">
              C++
            </span>
          </div>
          <a href="https://github.com/mvntando/LoRa" target="_blank" class="inline-flex items-center gap-1 mt-3 text-sm font-medium text-gray-700 hover:text-black decoration-gray-600 hover:decoration-gray-700 underline underline-offset-4 transition">
            View on GitHub
            <span aria-hidden="true">↗</span>
          </a>
        </div>
      </div>
    </div>

    <!-- More Projects Toggle -->
    <div class="mt-12">
      <button @click="showMore = !showMore" class="w-full p-4 flex items-center justify-between gap-3 rounded-xl border border-gray-300 bg-gray-50 text-gray-700 hover:bg-gray-100 hover:border-gray-400 transition">
        <span class="text-sm font-medium">
          Other Projects
        </span>
        <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5 transition-transform" :class="showMore ? 'rotate-180' : ''" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
        </svg>
      </button>
    </div>

    <transition enter-active-class="transition-all duration-300 ease-out" leave-active-class="transition-all duration-300 ease-in" enter-from-class="opacity-0 max-h-0" enter-to-class="opacity-100 max-h-[2000px]" leave-from-class="opacity-100 max-h-[2000px]" leave-to-class="opacity-0 max-h-0">
      <div v-if="showMore" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 mt-12 gap-12">
        <!-- Project 4 -->
        <div class="bg-gray-100 rounded-xl overflow-hidden border border-gray-300">
          <img src="../assets/imgs/portfolio.png" alt="Portfolio Website" class="w-full h-40 object-cover">
          <div class="p-5">
            <div class="flex items-center gap-3 mb-2">
              <svg class="size-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                <circle cx="12" cy="12" r="10"></circle>
                <line x1="2" y1="12" x2="22" y2="12"></line>
                <path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path>
              </svg>
              <h3 class="font-semibold">Portfolio Website</h3>
            </div>
            <p class="text-gray-700 mb-4">
              A responsive site built with Vue.js and Tailwind CSS, live on Vercel, presenting my projects, personal work, and ongoing development experiments.
            </p>
            <div class="flex flex-wrap gap-2 mb-4 justify-center text-xs font-medium">
              <span class="px-3 py-1 rounded-full text-green-800 border border-green-400">
                Vue.js
              </span>
              <span class="px-3 py-1 rounded-full text-blue-800 border border-blue-400">
                Tailwind CSS
              </span>
              <span class="px-3 py-1 rounded-full text-orange-800 border border-orange-400">
                Portfolio
              </span>
            </div>
            <a href="https://github.com/mvntando/Portfolio" target="_blank" class="inline-flex items-center gap-1 mt-3 text-sm font-medium text-gray-700 hover:text-black decoration-gray-600 hover:decoration-gray-700 underline underline-offset-4 transition">
              View on GitHub
              <span aria-hidden="true">↗</span>
            </a>
          </div>
        </div>

        <!-- Project 5 -->
        <div class="bg-gray-100 rounded-xl overflow-hidden border border-gray-300">
          <img src="../assets/imgs/pwm.jpeg" alt="Smart Water Monitor" class="w-full h-40 object-cover">
          <div class="p-5">
            <div class="flex items-center gap-3 mb-2">
              <svg xmlns="http://www.w3.org/2000/svg" class="size-6" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                <path d="M3 12h5v8h4v-16h4v8h5" />
              </svg>

              <h3 class="font-semibold">Pulse Width Modulator</h3>
            </div>
            <p class="text-gray-700 mb-4">
              Arduino sketch for generating PWM signals. Features adjustable frequency and duty cycle, with code optimized for low power consumption and precise timing.
            </p>
            <div class="flex flex-wrap gap-2 mb-4 justify-center text-xs font-medium">
              <span class="px-3 py-1 font-medium rounded-full text-orange-800 border border-orange-400">
                Arduino
              </span>
              <span class="px-3 py-1 font-medium rounded-full text-gray-900 border border-gray-500">
                C++
              </span>
              <span class="px-3 py-1 font-medium rounded-full text-green-800 border border-green-400">
                PWM
              </span>
            </div>
            <a href="https://github.com/mvntando/Pwm" target="_blank" class="inline-flex items-center gap-1 mt-3 text-sm font-medium text-gray-700 hover:text-black decoration-gray-600 hover:decoration-gray-700 underline underline-offset-4 transition">
              View on GitHub
              <span aria-hidden="true">↗</span>
            </a>
          </div>
        </div>

        <!-- Project 6 -->
      </div>
    </transition>
  </div>
</template>

<script setup>
import { ref } from 'vue';
import NavBar from '../components/NavBar.vue';

const showMore = ref(false);
</script>
