<script setup>
import SearchIcon from '@/components/icons/SearchIcon.vue';
import ProfileIcon from './icons/ProfileIcon.vue';
import LoveIcon from './icons/LoveIcon.vue';
import ShopIcon from './icons/ShopIcon.vue';
import Badge from './Badge.vue';
</script>


<template>
  <div class="flex justify-center items-center py-3 border-b-[1px]">

    <div class="flex items-center justify-between w-full max-w-6xl">

      <ul class="flex gap-4 items-center">
        <li>
          <a href="#">
            <ion-icon name="logo-facebook"></ion-icon>
          </a>
        </li>
        <li>
          <a href="#">
            <ion-icon name="logo-twitter"></ion-icon>
          </a>
        </li>
        <li>
          <a href="#">
            <ion-icon name="logo-instagram"></ion-icon>
          </a>
        </li>
        <li>
          <a href="#">
            <ion-icon name="logo-linkedin"></ion-icon>
          </a>
        </li>
      </ul>

      <div class="text-center px-6">
        <p class="text-xs font-semibold">
          <b>Free Shipping</b> This Week Order Over - $55
        </p>
      </div>

      <div class="flex text-xs gap-4">
        <select name="currency" class="border outline-none rounded-md p-1">
          <option value="usd">USD &dollar;</option>
          <option value="eur">EUR &euro;</option>
        </select>
        <select name="language" class="border outline-none rounded-md p-2">
          <option value="en-US">English</option>
          <option value="es-ES">Espa&ntilde;ol</option>
          <option value="fr">Fran&ccedil;ais</option>
        </select>
      </div>

    </div>

  </div>

  <div class="flex justify-center items-center space-x-52 mx-32 w-full max-w-6xl relative">
    <div>
      <RouterLink to="/">
        <h1 class="text-4xl font-bold">Mark<span class="text-red-600">i</span>t</h1>
      </RouterLink>
    </div>
    <div class="p-10 flex relative">
      <!-- Adjusted Search Icon position and removed absolute positioning -->
      <SearchIcon class="absolute my-3 mx-[20.7rem]" />
      <input 
        type="text" 
        placeholder="Enter product name to search..." 
        class="border border-gray-300 rounded p-2 pl-3 pr-8 focus:outline-none ease-in-out focus:ring-1 focus:ring-red-600"
      >
    </div>

    <div class="flex space-x-3">
      <div>
        <ProfileIcon />
      </div>
      <div>
        <Badge class="absolute mx-[1.1rem] -my-2" />
        <LoveIcon />
      </div>
      <div>
        <Badge class="absolute mx-[1.1rem] -my-2" />
        <ShopIcon />
      </div>
    </div>

  </div>

</template>


