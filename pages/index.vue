<template>
  <div class="flex flex-row items-center h-full">
    <div class="w-full h-full item-center flex flex-col items-center  relative">
      <div class="w-full h-64 bg-green-300 flex items-center justify-center ">
        <div class="h-32 w-32 absolute bg-blue-200 rounded-full shadow-2xl mx-auto">
          <img src="/ezzy.JPG" alt="" class="rounded-full h-32 w-32">
        </div>
      </div>
      <div class="h-1/2 bg-gray-700 flex-auto w-full justify-center items-cente text-center space-y-2 py-5">
        <h1 class="text-white text-4xl">
          Ezekiel Wachira
        </h1>
        <div class="text-2xl text-green-300">
          Software Engineer
        </div>
        <div class="text-xl text-green-200">
          Android (Java, Kotlin) | Full Stack | Laravel, Vue Js, Nuxt Js Typescript
        </div>
        <div class="flex flex-row justify-center space-x-2">
          <nuxt-link to="/" tag="a" class="text-white" target="blank">
            <span class="mdi mdi-facebook text-3xl" />
          </nuxt-link>
          <nuxt-link to="/" tag="a" class="text-white" target="blank">
            <span class="mdi mdi-twitter text-3xl" />
          </nuxt-link>
          <nuxt-link to="/" tag="a" class="text-white" target="blank">
            <span class="mdi mdi-linkedin text-3xl" />
          </nuxt-link>
          <nuxt-link to="/" tag="a" class="text-white" target="blank">
            <span class="mdi mdi-git text-3xl" />
          </nuxt-link>
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
