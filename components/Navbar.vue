<template>
    <div class="container mx-auto">
        <nav class="p-4"> 
        <div class="flex justify-between"> 
        <NuxtLink class="text-base hover:text-blue-600 font-normal text-blue-400" to="/"> 
            <img src="/logo.jpg" class="h-12 w-18 object-fill border rounded-full" alt="logo">
        </NuxtLink>
     <div class="flex justify-between gap-10 my-2">
        <NuxtLink to="/" class="text-base hover:text-blue-600 font-normal text-blue-400">Main</NuxtLink>
      <NuxtLink to="/home" class="text-base hover:text-blue-600 font-normal text-blue-400">Home</NuxtLink>
      <NuxtLink to="/about" class="text-base hover:text-blue-600 font-normal text-blue-400">About</NuxtLink>
      <NuxtLink class="text-base hover:text-blue-600 font-normal text-blue-400">Services</NuxtLink>
      <NuxtLink  class="text-base hover:text-blue-600 font-normal text-blue-400">Contact</NuxtLink>
        <NuxtLink class="text-base hover:text-blue-600 font-normal text-blue-400">Blog</NuxtLink>
     </div>
    </div>
    </nav>
    </div>
</template>