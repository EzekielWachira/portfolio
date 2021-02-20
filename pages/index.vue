<template>
  <div class="flex flex-row items-center h-full bg-gray-900 relative">
    <div class="w-full h-full item-center flex flex-col items-center pt-5">
      <div class="h-1/2 bg-gray-900 h-full w-full justify-center items-center text-center space-y-2 py-5">
        <div class="h-64 flex items-center justify-center ">
          <div class="rounded-full shadow-2xl mx-auto">
            <img src="/ezzy.JPG" alt="" class="rounded-full h-64 w-64">
          </div>
        </div>
        <h1 class="text-white text-4xl">
          Ezekiel Wachira
        </h1>
        <div class="text-2xl text-green-300">
          Software Engineer
        </div>
        <div class="text-xl text-green-200">
          Android (Java, Kotlin) | Full Stack | Laravel, Vue Js, Nuxt Js Typescript
        </div>
        <div class="flex flex-row justify-center items-center space-x-2">
          <nuxt-link to="/" tag="a" class="text-white py-2 px-2 rounded bg-blue-600" target="blank">
            <span class="mdi mdi-facebook text-3xl" />
          </nuxt-link>
          <nuxt-link to="/" tag="a" class="text-white py-2 px-2 rounded bg-green-500" target="blank">
            <span class="mdi mdi-twitter text-3xl" />
          </nuxt-link>
          <nuxt-link to="/" tag="a" class="text-white py-2 px-2 rounded bg-blue-800" target="blank">
            <span class="mdi mdi-linkedin text-3xl" />
          </nuxt-link>
          <nuxt-link to="/" tag="a" class="text-white py-2 px-2 rounded bg-orange-500" target="blank">
            <span class="mdi mdi-git text-3xl" />
          </nuxt-link>
          <nuxt-link to="/" tag="a" class="text-white py-2 px-2 rounded bg-red-600" target="blank">
            <span class="mdi mdi-email-outline text-3xl" />
          </nuxt-link>
        </div>
        <div class="flex justify-center space-x-2 mt-5 p-3">
          <button class="px-3 py-2 align-center flex rounded space-x-2 bg-green-400 text-white">
            <span class="text-md my-auto">Hire me</span>
            <span class="mdi mdi-emoticon-happy-outline text-2xl"></span>
          </button>
          <button class="px-3 py-2 align-center flex rounded space-x-2 bg-gray-600 text-white">
            <span class="text-md my-auto">Download CV</span>
            <span class="mdi mdi-file-download-outline text-2xl"></span>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
// import {PageLinks} from 'static/PageLinks'

// const links: PageLinks[] = [
//     { title: 'Home', icon: 'mdi-home', linkTo: '/' },
//     { title: 'About', icon: 'mdi-information', linkTo: '/' },
//     { title: 'Skills', icon: 'mdi-briefcase-outline', linkTo: '/' },
//     { title: 'Portfolio', icon: 'mdi-account-hard-hat', linkTo: '/' },
//     { title: 'Blog', icon: 'mdi mdi-post-outline', linkTo: '/' },
//     { title: "Contact", icon: 'mdi-chat-processing-outline', linkTo: '/' }
//   ]

export default Vue.extend({
  //
})
</script>
<style scoped>
/* .pic{
  background: url('/ezzy.jpg') no-repeat;
  background-size: cover;
  background-position: center;
} */

/*
.pick:after{
  background: inherit;
  bottom: 0;
  content: '';
  display: block;
  height: 50%;
  left: 0;
  position: absolute;
  right: 0;
  z-index: -1;
  -webkit-backface-visibility: hidden;
}
.pick:after{
  bottom: 0;
  transform: skew(-6deg);
  transform-origin: 100%;
} */
</style>
