<template>
  <div class="bg -z-30"></div>
  <div class=" mx-auto max-w-7xl px-10 py-6 flex h-screen w-full flex-col justify-between z-10">
    <div class="flex justify-between">
      <div>
        <img src="https://picsum.photos/100" alt="" class="h-12 w-12" />
      </div>
      <ul class="inline-flex space-x-6 text-white">
        <li>WORK</li>
        <li>ABOUT</li>
        <li>CONTACT</li>
      </ul>
    </div>
    <div class="flex lg:flex-row sm:flex-col lg:space-x-10 text-white">
      <div class="lg:w-1/3 ">
        <p class="font-extrabold text-6xl mb-6">Let's get started.</p>
        <span class="uppercase tracking-wide">Basic contact form</span>
      </div>
      <div class="lg:w-2/3 sm:mt-6">
        <p class="leading-loose text-3xl ">
          My name is
          <input type="text" id="nom" class="duration-300 border-b-[1px] border-b-black focus:bg-gray-500 w-96  bg-transparent outline-none ease-in focus:border-b-0 focus:px-2 uppercase" placeholder="Your full name" />
          and i have a
          <input type="text" id="job" class="duration-300 border-b-[1px] border-b-black focus:bg-gray-500 w-96 bg-transparent outline-none ease-in focus:border-b-0 focus:px-2 uppercase"
            placeholder="website full-time job etc" />
          that needs help. You can reach me at
          <input type="text" id="email" class="duration-300 border-b-[1px] border-b-black focus:bg-gray-500 w-96 bg-transparent outline-none ease-in focus:border-b-0 focus:px-2 uppercase" placeholder="your email address" />
          to get things started.
        </p>

        <div></div>
      </div>
    </div>
    <div>footer</div>
  </div>
</template>

<style lang="scss"></style>
