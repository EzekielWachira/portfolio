<template>
  <nav class="flex item-center justify-between flex-wrap bg-green-400 p-4 shadow-md">
    <div class="flex item-center flex-shrink-0 text-white mr-6">
      <nuxt-link to="/">
        <span class="font-bold text-xl">DroidDevExpress</span>
      </nuxt-link>
    </div>
    <div class="w-full bg-gray-900 block flex-grow sm:flex sm:items-center sm:w-auto">
      <div class="text-sm bg-gray-900 sm:flex-grow">
        <nuxt-link to="/portfolio" class="block mt-4 sm:inline-block sm:mt-0 text-teal-100 hover:text-white mr-4">
          Portfolio00
          <span class="mdi mdi-briefcase-outline" />
        </nuxt-link>
        <nuxt-link to="/blog" class="block mt-4 sm:inline-block sm:mt-0 text-teal-100 hover:text-white mr-4">
          Blog
          <span class="mdi mdi-post-outline" />
        </nuxt-link>
        <nuxt-link to="/about" class="block mt-4 sm:inline-block sm:mt-0 text-teal-100 hover:text-white mr-4">
          About me
          <span class="mdi mdi-information-outline" />
        </nuxt-link>
        <nuxt-link to="/contact" class="block mt-4 sm:inline-block sm:mt-0 text-teal-100 hover:text-white mr-4">
          Contact me
          <span class="mdi mdi-account-box-outline" />
        </nuxt-link>
      </div>
      <div>
        <nuxt-link to="/" class="inline-block text-sm  px-4 py-2 leading-none border rounded text-white border-white  hover:border-transparent hover:text-blue-500 hover:bg-white mt-4 md:mt-0">
          Login
          <span class="mdi mdi-login-variant" />
        </nuxt-link>
      </div>
    </div>
  </nav>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  //
})
</script>
