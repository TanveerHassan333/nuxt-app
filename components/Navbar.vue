<template>
    <VContainer>
      <div class="d-flex justify-space-between">
        <NuxtLink class="mt-0">
            <VAvatar size="70"> <VImg src="@/public/logo.jpg"></VImg></VAvatar>
        </NuxtLink>
        <div class="d-flex justify-space-between gap-6">
            <NuxtLink to="/" class="">Main</NuxtLink>
                <NuxtLink to="/home" class="">Home</NuxtLink>
                <NuxtLink to="/about" class="">About</NuxtLink>
                <NuxtLink class="">Services</NuxtLink>
                <NuxtLink class="">Contact</NuxtLink>
                <NuxtLink class="">Blog</NuxtLink>
        </div>
      </div>
    </VContainer>
</template>
