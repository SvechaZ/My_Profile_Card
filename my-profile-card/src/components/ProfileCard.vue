<script setup>
    const background = '/ที่อยู่หมอ.jpg'
    const profileImg = '/หมอGPT.jpg'
defineProps({
  background: String,
  profileimg: String,
  name: String,
  subheading: String,
  followers: String,
  following: String,
  projects: String
})

</script>

<template>
  <!-- Card -->
  <div class="bg-white shadow-lg rounded-2xl overflow-hidden text-center max-w-sm mx-auto">
    
    <!-- Header -->
    <div
      class="relative min-h-32 bg-cover bg-center"
      :style="{ backgroundImage: `url(${background})` }"
    >
      <img
        :src="profileImg"
        alt="Profile Image"
        class="w-32 h-32 rounded-full object-cover border-[4px] border-white
               absolute top-full left-1/2 transform -translate-x-1/2 -translate-y-1/2"
      />
    </div>

    <!-- Content -->
    <div class="px-6 pt-20 pb-6">
      <h2 class="font-bold text-gray-800 text-2xl mb-2">{{ name }}</h2>
      <h3 class="text-gray-600 text-lg">{{ subheading }}</h3>
    </div>
    <!-- Status -->
     <div class="flex border-t border-gray-200">
        <!-- Followers -->
        <div class="flex-1 py-4 text-center">
            <p class="text-gray-400 text-sm">Followers</p>
            <p class="text-xl font-bild text-gray-800">{{ followers }}</p>
        </div>

        <!-- Follwering -->
         <div class="flex-1 py-4 text-center  ">
            <p class="text-gray-400 tect-gray-400 text-sm">{{ followers }}</p>
            <p class="text-xl font-bolde text-gray-800">548</p>
         </div>

         <!-- Projects -->

         <div class="flex-1 py-4 text-center  ">
            <p class="text-gray-400 tect-gray-400 text-sm">{{ followers }}</p>
            <p class="text-xl font-bolde text-gray-800">12</p>
         </div>
     </div>
  </div>

</template>

<style scoped>

</style>