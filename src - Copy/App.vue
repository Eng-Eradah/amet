<template>
<div class="font-sans antialiased" id="app">
  <nav class="flex items-center justify-between flex-wrap bg-primary-600 p-6">
    <div class="flex items-center flex-no-shrink text-white mr-6">
      <svg class="fill-current h-8 w-8 mr-2" width="54" height="54" viewBox="0 0 54 54" xmlns="http://www.w3.org/2000/svg"><path d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z"/></svg>
      <span class="font-semibold text-xl tracking-tight">Tailwind CSS</span>
    </div>
    <div class="block sm:hidden">
      <button @click="toggle()" class="flex items-center px-3 py-2 border rounded text-primary-200 border-teal-light hover:text-white hover:border-white">
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
      </button>
    </div>
    <div :class="open ? 'block': 'hidden'" class="w-full flex-grow sm:flex sm:items-center sm:w-auto">
      <div class="text-sm sm:flex-grow">
        <a href="#responsive-header" class="no-underline block mt-4 sm:inline-block sm:mt-0 text-primary-200 hover:text-white mr-4">
        
      <router-link to="/sha">Shatha</router-link> 
        </a>
        <a href="#responsive-header" class="no-underline block mt-4 sm:inline-block sm:mt-0 text-primary-200 hover:text-white mr-4">
         
      <router-link to="/enas">Enas</router-link> 
        </a>
        <a href="#responsive-header" class="no-underline block mt-4 sm:inline-block sm:mt-0 text-primary-200 hover:text-white">
         
      <router-link to="/sheba">Sheba</router-link> 
        </a>
      </div>
      <div>
        <a href="#" class="no-underline inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal hover:bg-white hover:text-primary-900  mt-4 sm:mt-0">login</a>
      </div>
    </div>
  </nav>
  
  <router-view />
</div>

</template>

<script>



export default {
  
  name: 'App',
  components: {
  },
  data(){
    return{
      open:false,
    }
  }
  ,
  methods:{
    toggle()
    {
      this.open = !this.open
    }
  }
 

}
</script>

<style>

</style>
