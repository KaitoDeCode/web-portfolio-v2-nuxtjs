<template>
  <div class="min-h-screen  flex justify-center items-center border">
    <div class="">
      <div v-if="mode === 'Adi' ">
        <img class="w-40 h-40 rounded-full mx-auto block border-8 border-black" src="~/assets/img/adi.jpeg" alt="">
        <h1 class="text-3xl font-bold text-center uppercase">Adi <span class="text-red-700">Kurniawan</span></h1>
        <hr class="h-1 bg-black">
        <p class="mb-3">Software Engineering Student || Junior Programmer</p>
      </div>
      <div v-if="mode === 'Kaito'">
        <img class="w-40 h-40 object-cover mx-auto block rounded-full border-8 border-red-700" src="~/assets/img/kaito.jpg" alt="">
        <h1 class="text-center text-3xl uppercase font-bold">KaitoDe<span class="text-red-700">Code</span></h1>
        <hr class="h-1 bg-black">
        <p class="mb-3">Junior Web Develor || Junior Mobile Developer || Linux User</p>
      </div>
      
      <div class="flex justify-center items-center">
        <button @click="changeMode('Adi')"  class="bg-black text-white px-5 py-1 w-40">Adi</button>
        <button @click="changeMode('Kaito')"  class="bg-red-700 px-5 py-1 w-40 text-white">Kaito</button>
      </div>
    </div>
  </div>
</template>
<script>
  export default{
    data(){
      return{
        mode : "Adi"
      }
    },
    methods: {
      changeMode(mode){
        this.mode = mode;
      }
    },
  }
</script>