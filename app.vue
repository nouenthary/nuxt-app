import Home from './server/pages/home/Home.vue';
<template>
  <div>
    <NuxtLink to="/"> Home </NuxtLink>

    <NuxtLink to="/home/home"> Home </NuxtLink>

    <NuxtLink to="/about/about"> About </NuxtLink>

    <div>
      <NuxtLayout>
        <NuxtPage />
      </NuxtLayout>
    </div>
  </div>
</template>
