<script setup>
import ProfileCard from './components/ProfileCard.vue';


</script>

<template>
  <div class="min-h-screen flex flex-wrap gap-8 items-center justify-center bg-gradient-to-br from-[#0f0f1a] via-[#1b0f2f] to-purple-700">
              
    <ProfileCard
      background="/bg.jpg"
      profileimg="/profile03.png"
      name="Siriyakon"
      subheading="Student, IT"
      followers="1,200"
      following="548"
      projects="12"
      instagram="https://www.instagram.com/siri_yx/"
      facebook="https://www.facebook.com/tan.siriyagon"
    />

    <ProfileCard
      background="/bg.jpg"
      profileimg="/profile01.jpg"
      name="Thanasron"
      subheading="Student, IT"
      followers="980"
      following="410"
      projects="8"
      instagram="https://www.instagram.com/savaki_tns/"
      facebook="https://www.facebook.com/thanasorn.dujsadeeroj.7"
    />

    <ProfileCard
      background="/bg.jpg"
      profileimg="/profile02.jpg"
      name="Kanok"
      subheading="Student, IT"
      followers="1,540"
      following="600"
      projects="15"
      instagram="https://www.instagram.com/k_nodpok/"
      facebook="https://www.facebook.com/kanokpon.suebyam.908"
    />          
              
            
  </div>
</template>

<style scoped>
  
</style>
