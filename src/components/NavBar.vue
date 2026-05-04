<template>

<nav class="fixed w-full bg-gray-50 top-0 left-0 right-0">
<div class="max-w-7xl mx-auto px-4 sm:px-6 md:px-12 lg:px-20 py-3 md:py-4
flex items-center justify-between">

<!-- logo -->
<div class="flex items-center text-xl sm:text-2xl font-bold
 text-gray-500">

 <div class="w-8 h-8 sm:w-10 sm:h-10 flex items-center 
 justify-center rounded-full border-3 sm:border-4 border-pink-600
 text-pink-600 mr-2">H</div>
 <span>ro <span class="text-yellow-500">service</span></span>
</div>

<!-- links -->
 <div>
    <ul class="hidden md:flex items-center gap-6 lg:gap-8
     text-gray-700 font-medium">
<li v-for="item in menuItems" :key="item.name"
class="hover:text-green-500 cursor-pointer transition-colors">

<a :href="item.path">{{ item.name }}</a></li>
    </ul>
 </div>
</div>
</nav>
</template>

<script setup>

const menuItems=[
    {name:"Home",path:"#"},
    {name:"About",path:"#about"},
    {name:"Company",path:"#company"},
    {name:"Services",path:"#services"},
    {name:"Contact",path:"#contact"},
]
</script>