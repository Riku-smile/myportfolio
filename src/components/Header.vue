<template lang="html">
  <div id="header" class="container mx-auto z-50">
    <div class="bg-white flex justify-between items-center h-16 w-full">
      <div>
        <button class="flex items-center px-3 py-2 text-black" @click="isOpen = !isOpen">
          <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
              <path v-show="!isOpen" d="M24 6h-24v-4h24v4zm0 4h-24v4h24v-4zm0 8h-24v4h24v-4z"/>
              <path v-show="isOpen" d="M24 20.188l-8.315-8.209 8.2-8.282-3.697-3.697-8.212 8.318-8.31-8.203-3.666 3.666 8.321 8.24-8.206 8.313 3.666 3.666 8.237-8.318 8.285 8.203z"/>
          </svg>
        </button>
      </div>
      <h1 class="text-xl font-bold border-4 mx-auto">Riku's PortFolio</h1>
    </div>
    <transition name="nav">
    <nav id="tnav" v-if="isOpen" class="bg-gray-200 flex lg:block fixed lg:static left-0 w-full h-full lg:h-auto overflow-y-scroll" :class="isOpen ? 'block' : 'hidden'">
      <ul class="flex flex-col lg:flex-row lg:justify-center w-full text-center">
        <li class="border-b"><router-link to="/" class="block px-8 py-2 my-4 hover:bg-gray-400 rounded">Home</router-link></li>
        <li class="border-b"><router-link to="/about" class="block px-8 py-2 my-4 hover:bg-gray-400 rounded">About</router-link></li>
        <li class="border-b"><router-link to="/work" class="block px-8 py-2 my-4 hover:bg-gray-400 rounded">Work</router-link></li>
        <li class="border-b"><router-link to="/#" class="block px-8 py-2 my-4 hover:bg-gray-400 rounded">News(#)</router-link></li>
        <button class="mx-auto lg:mx-0">
          <router-link to="/form" class="block px-8 py-2 my-4 bg-orange-400 hover:opacity-75 rounded-full">Contact</router-link>
        </button>
      </ul>
    </nav>
    </transition>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data: function () {
    return {
      isOpen: false
    }
  }
}
</script>

<style lang="css" scoped>
.nav-enter-active{
  transition: all .5s ease;
}

.nav-leave-active{
  transition: all .5s ease;
}

.nav-enter, .nav-leave-to{
  transform: translateX(10px);
  opacity: 0;
}
</style>
