<template>
  <div class="bg-green-200">
    <div class="container mx-auto px-6">
        <div class="h-screen flex flex-row space-x-2 py-5 ">
    <div class="h-full w-20 items-center flex flex-col flex-column justify-center flex-none">
      <div class="shadow-lg w-full rounded">
        <nuxt-link to="/" class="w-full flex flex-col items-center shadow-lg">
          <div class="w-full bg-white border-1 border-gray-300 flex flex-col items-center">
            <span class="mdi mdi-home text-3xl" />
            <span>Home</span>
          </div>
        </nuxt-link>
        <nuxt-link to="/about" class="w-full flex flex-col items-center shadow-lg">
          <div class="w-full bg-white border-t border-1 border-gray-300 flex flex-col items-center">
            <span class="mdi mdi-information text-3xl" />
            <span>About</span>
          </div>
        </nuxt-link>
        <nuxt-link to="/" class="w-full flex flex-col items-center shadow-lg">
          <div class="w-full bg-white border-t border-1 border-gray-300 flex flex-col items-center">
            <span class="mdi mdi-briefcase-outline text-3xl" />
            <span>Skills</span>
          </div>
        </nuxt-link>
        <nuxt-link to="/portfolio" class="w-full flex flex-col items-center shadow-lg">
          <div class="w-full bg-white border-t border-1 border-gray-300 flex flex-col items-center">
            <span class="mdi mdi-map-legend text-3xl" />
            <span>Portfolio</span>
          </div>
        </nuxt-link>
        <nuxt-link to="/" class="w-full flex flex-col items-center shadow-lg">
          <div class="w-full bg-white border-t border-1 border-gray-300 flex flex-col items-center">
            <span class="mdi mdi-post-outline text-3xl" />
            <span>Blog</span>
          </div>
        </nuxt-link>
        <nuxt-link to="/" class="w-full flex flex-col items-center shadow-lg">
          <div class="w-full bg-white border-t border-1 border-gray-300 flex flex-col items-center">
            <span class="mdi mdi-file-document-outline text-3xl" />
            <span>Resume</span>
          </div>
        </nuxt-link>
        <nuxt-link to="/" class="w-full flex flex-col items-center shadow-lg">
          <div class="w-full bg-white border-t border-1 border-gray-300 flex flex-col items-center">
            <span class="mdi mdi-chat-processing-outline text-3xl" />
            <span>Contact</span>
          </div>
        </nuxt-link>
      </div>
    </div>
    <div class="flex-auto bg-white rounded shadow-2xl">
      <Nuxt />
    </div>
  </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
// import Navbar from '@/components/Navbar'
export default Vue.extend({
  components: {
    // Navbar
  }
})
</script>

<style>

html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
</style>
