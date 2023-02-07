<template>
  
  <div class="text-lg bg-red-500 text-white h-10 flex items-center mx-auto px-4 shadow">
    <router-link to="/" class="flex items-center h-10 px-2">Home</router-link> |
    <router-link to="/addpost" class="flex items-center h-10 px-2">Add Post</router-link> |
    <router-link to="/about" class="flex items-center h-10 px-2">About</router-link>
  </div>

  <RouterView />
</template>

<script>
  export default{
    name:"Vue3-Blog"
  }
</script>