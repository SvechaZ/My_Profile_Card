<script setup>
import ProfileCard from './components/ProfileCard.vue';


</script>

<template>
  <div class="min-h-screen flex items-center justify-center bg-gradient-to-br from-[#0f0f1a] via-[#1b0f2f] to-purple-700">

    <ProfileCard
    background="./src/assets/background.jpg"
      profileimg="./src/assets/profile.jpg"
      name="Siriyakon Sangkaew"
      subheading="Student, 20, IT"
     followers="1,200"
      following="548"
      projects="12" 
    />
  </div>

</template>

<style scoped>
  
</style>
