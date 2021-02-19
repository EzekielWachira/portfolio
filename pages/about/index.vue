<template>
  <div class="container h-full w-full bg-gray-900 justify-center flex p-10">
    <div class="w-10/12 h-auto  rounded overflow-y-auto main-card pr-2 main">
      <div class="text-white flex flex-col">
        <span class="font-bold border- border-l-8 pl-2 border-green-400 text-xl">EZEKIEL WACHIRA</span>
        <span class="font-semibold text-green-400 text-MD pl-4">ASSOCIATE ANDROID DEVELOPER</span>
        <span class="font-semibold text-gray-400 text-MD pl-4">SOFTWARE ENGINEER</span>
      </div>
      <div class="border-l-8 border-green-400 pl-2 font-semibold text-lg mt-5 text-gray-300">WHO I AM</div>
      <div class="mt-3">
        <article class="text-md text-gray-500 leading-7 font-semibold about">I'm a software engineer specializing with Android Development using both Java and Kotlin, Full-Stack developer</article>
        <article class=" text-gray-500 leading-7 font-semibold about">As a passionate software engineer. I have been working as a web developer developing
          projects with Laravel framework, Vue JS, Nuxt JS and Typescript, Android projects with Java
          and Kotlin.
          Proficient in utilizing a wide variety of programs and tools to provide high quality and cost -
          effective applications and systems to boost organizational efficiency and productivity.
          Possess unmatched coding and testing skills to deliver high quality systems.
        </article>
      </div>
      <div class="border-l-8 border-green-400 pl-2 font-semibold text-lg mt-5 text-gray-300">MY CERTIFICATIONS</div>
      <div class="flex flex-row">
        <div class="shadow-lg text-center bg-gray-800 rounded border-green-400 border-2 w-4/12 px-5 py-2 card pl-2 font-semibold text-lg mt-5 text-gray-300">
          <span class="underline">ASSOCIATE ANDROID DEVELOPER</span>
          <article class="font font-medium">Google certified android developer</article>
        </div>
      </div>
      <div class="border-l-8 border-green-400 pl-2 font-semibold text-lg mt-5 text-gray-300">TESTIMONIALS</div>
      <div class="flex flex-row space-x-2 testimonials">
        <div class="shadow-lg text-center bg-gray-800 rounded border-green-400 border-2 w-4/12 px-5 py-2 card pl-2  text-lg mt-5 text-gray-300 testimonial">
          <span class="underline font-semibold">John Doe</span>
          <article class="font ">
            <span class="font-semibold">&ldquo;</span>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet ea, iusto consectetur expedita eum temporibus quas numquam eos itaque quo. Cumque illum placeat molestias voluptatum assumenda, ad ducimus eligendi maxime.
            <span>&rdquo;</span>
          </article>
        </div>
        <div class="shadow-lg text-center bg-gray-800 rounded border-green-400 border-2 w-4/12 px-5 py-2 card pl-2  text-lg mt-5 text-gray-300 testimonial">
          <span class="underline font-semibold">John Doe</span>
          <article class="font ">
            <span class="font-semibold">&ldquo;</span>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet ea, iusto consectetur expedita eum temporibus quas numquam eos itaque quo. Cumque illum placeat molestias voluptatum assumenda, ad ducimus eligendi maxime.
            <span>&rdquo;</span>
          </article>
        </div>
        <div class="shadow-lg text-center bg-gray-800 rounded border-green-400 border-2 w-4/12 px-5 py-2 card pl-2  text-lg mt-5 text-gray-300 testimonial">
          <span class="underline font-semibold">John Doe</span>
          <article class="font ">
            <span class="font-semibold">&ldquo;</span>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Amet ea, iusto consectetur expedita eum temporibus quas numquam eos itaque quo. Cumque illum placeat molestias voluptatum assumenda, ad ducimus eligendi maxime.
            <span>&rdquo;</span>
          </article>
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
.main-card::-webkit-scrollbar{
  width: .40rem;
  background: rgb(62, 61, 68);
  border-radius: 5px;
}
.main-card::-webkit-scrollbar-thumb{
  width: .40rem;
  background: rgb(5, 182, 123);
  border-radius: 5px;
}

@media screen and (max-width: 500px) {
  .testimonias{
    display: block;
  }
  .testimonial{
    width: auto;
  }
  .container{
    padding: 5px;
  }
  .main{
    width: 100%;
  }
  .about{
    font-size: 16px;
    font-weight: normal;
  }
}
</style>
