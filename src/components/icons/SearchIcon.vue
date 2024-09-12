<script setup>

defineProps({
  props: {
    sizeClass: {
      type: String,
      default: 'size-6', // Customize as needed, based on Tailwind or other CSS class
    },
    strokeWidth: {
      type: Number,
      default: 1.5,
    },
    viewBox: {
      type: String,
      default: '0 0 24 24',
    },
  },
})

</script>

<template>
  <!-- <svg xmlns="http://www.w3.org/2000/svg" fill="none" :viewBox="viewBox" :stroke-width="strokeWidth" stroke="currentColor"
    :class="sizeClass">
    <path stroke-linecap="round" stroke-linejoin="round"
      d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
  </svg> -->
  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-4">
  <path stroke-linecap="round" stroke-linejoin="round" d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
</svg>

</template>


