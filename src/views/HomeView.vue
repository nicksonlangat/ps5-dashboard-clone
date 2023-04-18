<template>
  <div class="bg-center bg-cover w-full"  :style="{ 'background-image': 'url(' + require('../assets/forspoken.jpg') +')', 'height':'100vh'}">
    <div class="flex justify-between">
      <div class="flex gap-12 ml-8">
        <h3 class="text-white cursor-pointer font-bold text-2xl mt-8">
          Games
        </h3>
        <h3 class="text-gray-600 cursor-pointer text-2xl mt-8">
          Media
        </h3>
      </div>

      <div class="flex gap-6 mr-6 mt-8">
        <span class="text-white text-4xl mt-1">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
          </svg>
        </span>

        <span class="text-white text-4xl mt-1">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
            <path stroke-linecap="round" stroke-linejoin="round" d="M10.343 3.94c.09-.542.56-.94 1.11-.94h1.093c.55 0 1.02.398 1.11.94l.149.894c.07.424.384.764.78.93.398.164.855.142 1.205-.108l.737-.527a1.125 1.125 0 011.45.12l.773.774c.39.389.44 1.002.12 1.45l-.527.737c-.25.35-.272.806-.107 1.204.165.397.505.71.93.78l.893.15c.543.09.94.56.94 1.109v1.094c0 .55-.397 1.02-.94 1.11l-.893.149c-.425.07-.765.383-.93.78-.165.398-.143.854.107 1.204l.527.738c.32.447.269 1.06-.12 1.45l-.774.773a1.125 1.125 0 01-1.449.12l-.738-.527c-.35-.25-.806-.272-1.203-.107-.397.165-.71.505-.781.929l-.149.894c-.09.542-.56.94-1.11.94h-1.094c-.55 0-1.019-.398-1.11-.94l-.148-.894c-.071-.424-.384-.764-.781-.93-.398-.164-.854-.142-1.204.108l-.738.527c-.447.32-1.06.269-1.45-.12l-.773-.774a1.125 1.125 0 01-.12-1.45l.527-.737c.25-.35.273-.806.108-1.204-.165-.397-.505-.71-.93-.78l-.894-.15c-.542-.09-.94-.56-.94-1.109v-1.094c0-.55.398-1.02.94-1.11l.894-.149c.424-.07.765-.383.93-.78.165-.398.143-.854-.107-1.204l-.527-.738a1.125 1.125 0 01.12-1.45l.773-.773a1.125 1.125 0 011.45-.12l.737.527c.35.25.807.272 1.204.107.397-.165.71-.505.78-.929l.15-.894z" />
            <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
          </svg>
        </span>

        <span class="text-white text-4xl mt-1">
          <img class="h-8 rounded-full" src="../assets/user.jpeg" alt="">
        </span>

        <h3 class="text-white font-bold text-4xl">
          12:26
        </h3>
      </div>
    </div>


    <div class="ml-8 mt-8 grid grid-cols-10 gap-x-2">
      <div class="flex">
        <img class="h-48 rounded-lg shadow-md hover:border-sky-600 border cursor-pointer border-4" src="../assets/fifa.jpeg" alt="">
      </div>
      <div>
        <img class="h-36 rounded-lg shadow-md cursor-pointer" src="../assets/god.jpeg" alt="">
      </div>
      <div>
        <img class="h-36 rounded-lg shadow-md cursor-pointer" src="../assets/hog.jpeg" alt="">
      </div>
      <div>
        <img class="h-36 rounded-lg shadow-md cursor-pointer" src="../assets/wwii.jpeg" alt="">
      </div>
      <div>
        <img class="h-36 rounded-lg shadow-md cursor-pointer" src="../assets/spider.jpeg" alt="">
      </div>
      <div>
        <img class="h-36 rounded-lg shadow-md cursor-pointer" src="../assets/lou.jpeg" alt="">
      </div>
      <div>
        <img class="h-36 rounded-lg shadow-md cursor-pointer" src="../assets/rd.jpeg" alt="">
      </div>
      <div>
        <img class="h-36 rounded-lg shadow-md cursor-pointer" src="../assets/re.jpeg" alt="">
      </div>
    </div>

    <div class="ml-6 mt-80 flex justify-between">
      <div class="w-1/2">
        <div class="flex gap-4">
        <button class="rounded-full text-white bg-gray-900/80 px-12 py-2">
        Play Game
      </button>
      <span class="rounded-full text-white px-3 cursor-pointer py-2 bg-gray-900/80">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-8 h-8">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 12a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM12.75 12a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM18.75 12a.75.75 0 11-1.5 0 .75.75 0 011.5 0z" />
        </svg>

      </span>
      </div>
      </div>

      <div>
        <div class="w-56 mr-16">
        <div class="bg-gray-900/80 px-4 py-1">
          <div class="flex gap-16">
            <h3 class="cursor-pointer text-gray-400">Progress</h3>
            <h3 class="cursor-pointer text-gray-400">Earned</h3>
          </div>
          <div class="flex gap-16">
            <h3 class="text-white">20%</h3>
            <h3 class="text-white ml-8">12/42</h3>
          </div>
          <div class="flex gap-8 mt-4">
           <div class="inline-flex gap-4 text-white">
            <img class="h-6" src="../assets/PikPng.com_gold-cup-png_3386867.png" alt=""> 0
           </div>
           <div class="inline-flex gap-4 text-white">
           <img class="h-6" src="../assets/PikPng.com_trophy-vector-png_5488316.png" alt=""> 2
           </div>
           <div class="inline-flex gap-4 text-white">
           <img class="h-6" src="../assets/PikPng.com_cricket-trophy-png_385629.png" alt=""> 10
           </div>
          </div>
        </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  components: {
  }
}
</script>
