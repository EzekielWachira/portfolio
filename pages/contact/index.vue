<template>
  <div class="flex flex-col w-full h-full items-center py-2 relative bg-gray-900">
    <div class="shadow-md bg-gray-900 py-2 h-16 w-full justify-center text-center">
      <div class="text-3xl text-green-400 my-auto">
        Contact me
      </div>
    </div>
    <form class="mt-5 flex flex-col h-auto justify-center pb-2 w-1/2 w:sm-full">
      <input type="text" placeholder="name" class="border-2 bg-gray-900 focus:bg-gray-900 focus:outline-none text-white border-gray-500  py-3 px-2 rounded mt-3" />
      <input type="email" placeholder="email" class="border-2  bg-gray-900 focus:bg-gray-900 focus:outline-none text-white border-gray-500 py-3 px-2 rounded mt-3" />
      <textarea cols="10" rows="5" placeholder="Your message" class="mt-2  bg-gray-900 focus:bg-gray-900 focus:outline-none text-white border-gray-500 border-2 py-2 px-5 rounded"/>
      <div>
        <button class="border-green-500 space-x-2 border-2 text-white text-xl rounded px-5 py-2 mt-5 w-auto content-center flex flex-row justify-evenly hover:bg-green-500" type="submit">
          <span>Send message</span>
          <span class="mdi mdi-send-outline text-green-200 text-2xl"/>
        </button>
      </div>
    </form>
    <!--<div class="flex justify-start items-start px-5 py-2 shadow-2xl text-s bold py-5 flex-col absolute right-0 bottom-0 border-l border-t border-green-200">
      <div class="text-2xl bold my-2 text-green-400">Or reach me via</div>
      <div class="flex flex-row">
        <span class="mdi mdi-email text-2xl text-gay-700" />
        <div class="text-xl">ezekielwachira048@gmail.com</div>
      </div>
      <div class="flex flex-row">
        <span class="mdi mdi-twitter text-2xl text-gay-700" />
        <div class="text-xl">@EzekielWachira</div>
      </div>
      <div class="flex flex-row">
        <span class="mdi mdi-linkedin text-2xl text-gay-700" />
        <a class="text-xl" target="_blank" href="www.linkedin.com/in/ezekielwachira">Linkedin</a>
      </div>
    </div>-->
  </div>
</template>
