<template>
  <div id="app" class="font-maven">
    <div id="nav" class="flex py-4 bg-blue-800 text-white">
      <div class="container flex justify-between">
        <a  href="/" class="font-bold text-lg">My Profile</a>
        <div class="font-semibold">  
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About</router-link>
        </div>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
</style>
