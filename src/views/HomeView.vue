<template>
  <div class="home">
    <banner-form></banner-form>
    <div class="bg-gray-400 p-6">
      <h1 class="text-2xl text-sky-700 font-bold flex items-center">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-14 h-14"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M4.26 10.147a60.436 60.436 0 00-.491 6.347A48.627 48.627 0 0112 20.904a48.627 48.627 0 018.232-4.41 60.46 60.46 0 00-.491-6.347m-15.482 0a50.57 50.57 0 00-2.658-.813A59.905 59.905 0 0112 3.493a59.902 59.902 0 0110.399 5.84c-.896.248-1.783.52-2.658.814m-15.482 0A50.697 50.697 0 0112 13.489a50.702 50.702 0 017.74-3.342M6.75 15a.75.75 0 100-1.5.75.75 0 000 1.5zm0 0v-3.675A55.378 55.378 0 0112 8.443m-7.007 11.55A5.981 5.981 0 006.75 15.75v-1.5"
          />
        </svg>

        ESPACIO LIBRE PARA INCLUIR CONTENIDO
      </h1>
    </div>
    <div class=" px-2 grid md:grid-cols-4">
      <div
        v-for="index in 4"
        :key="index"
        class="p-6 bg-white border border-gray-200 rounded-lg shadow m-2"
      >
        <a href="#">
          <h5
            class="mb-2 text-2xl font-semibold tracking-tight"
            :class="[index < 4 ? 'text-sky-700' : 'text-red-700']"
          >
            Lorem Ipsu
          </h5>
        </a>
        <p class="mb-3 font-normal text-gray-500 dark:text-gray-400">
          Go to this step by step guideline process on how to certify for your
          weekly benefits:
        </p>
      </div>
    </div>
  </div>
</template>

<script>
import BannerForm from '@/components/BannerForm.vue';
export default {
  name: "HomeView",
  components:{
    BannerForm,

  }
};
</script>
