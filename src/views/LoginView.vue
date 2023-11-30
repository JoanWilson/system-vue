<script>
import FormLogin from '../components/FormLogin.vue';

export default {
  components: {
    FormLogin
  }
}
</script>

<template>
  <div class="grid h-screen bg-black">
    <div class="grid place-items-center h-screen relative">
      <div class="absolute bg-cover bg-center bg-no-repeat h-screen w-screen bg-[url('@/assets/star-background.jpg')] grid grid-cols-2">
        
        <div class="col-span-1 col-end-3"><img class="w-35 h-35" src="../assets/code-crafters.png" /></div>
      </div>
      <div class="grid relative h-screen w-screen">
        <div class="bg-white w-full sm:w-4/4 md:w-1/2 lg:w-2/5 xl:w-1/3 p-4 rounded shadow">
          <form-login />
        </div>
      </div>
    </div>
  </div>
</template>