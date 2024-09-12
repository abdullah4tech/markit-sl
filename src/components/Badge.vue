
<script setup lang="ts">
import { ref } from 'vue';


const counter = ref(0)

</script>

<template>
  <!-- <div class="flex items-center justify-center text-white text-xs font-bold bg-red-700 rounded-lg p-1">
    <p>{{ counter }}</p>
  </div> -->
  <div class="bg-red-600 text-white text-xs rounded-[20px] px-[4px] py-[0.5px]">
    <p>{{ counter }}</p>
  </div>
</template>