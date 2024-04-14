<script setup lang="ts">
import SmallArrowDown from '../icons/SmallArrowDown.vue';
import Vector from '../icons/Vector.vue';
import World from '../icons/World.vue';
</script>

<template>
  <div class="flex justify-between">
    <div class="flex">
      <img class="w-52" src="https://www.figma.com/file/SIOQhFFSd8oaX4JeobE16d/image/4eb58712eb0289898d0b9e17674da8021192c1ac" alt="Soroboom">
      <div class="flex items-center justify-between rounded-3xl bg-white w-fit">
        <div class="p-[14px] rounded-3xl bg-[#EC6A1F]">
          <Vector color="white" :size="18" />
        </div>
        <span class="font-montserrat px-4 text-[14px]">ПРАГА</span>
      </div>
    </div>
    <div class="flex">
      <div class="bg-black flex text-white items-center">
        <World :size="14" color="white" />
        <div class="flex gap-1 items-center">
          <span class="font-montserrat">RU</span>
          <SmallArrowDown :size="16" color="white" />
        </div>
      </div>
      <div>
      </div>
    </div>
  </div>
</template>