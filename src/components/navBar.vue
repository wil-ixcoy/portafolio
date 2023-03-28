<template>
  <nav class="bg-red-800">
    <div class="mx-auto px-4 py-2 sm:flex sm:justify-between sm:items-center">
      <div class="flex justify-between items-center">
        <div class="text-colorwhite font-bold text-lg">Mi sitio web</div>
        <button type="button" class="sm:hidden text-colorwhite hover:text-primary focus:outline-none focus:text-primary" @click="toggleMenu">
          <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
            <path v-if="menuOpen" fill-rule="evenodd" clip-rule="evenodd" d="M19 14H5v-1h14v1zM19 9H5V8h14v1zM5 15h14v1H5v-1z"/>
            <path v-else fill-rule="evenodd" clip-rule="evenodd" d="M4 6h16v1H4V6zm16 4H4v1h16v-1zm0 4H4v1h16v-1z"/>
          </svg>
        </button>
      </div>
      <div class="hidden sm:flex sm:items-center" :class="{ 'block': menuOpen }">
        <div class="flex flex-col sm:flex-row sm:ml-6">
          <a href="#" @click.prevent="scrollToSection('inicio')" class="px-3 py-2 rounded-md text-sm font-medium text-colorwhite hover:text-primary hover:bg-red-700 focus:outline-none focus:text-primary focus:bg-red-700">Inicio</a>
          <a href="#" @click.prevent="scrollToSection('sobre-mi')" class="mt-3 sm:mt-0 px-3 py-2 rounded-md text-sm font-medium text-colorwhite hover:text-primary hover:bg-red-700 focus:outline-none focus:text-primary focus:bg-red-700">Sobre mí</a>
          <a href="#" @click.prevent="scrollToSection('proyectos')" class="mt-3 sm:mt-0 px-3 py-2 rounded-md text-sm font-medium text-colorwhite hover:text-primary hover:bg-red-700 focus:outline-none focus:text-primary focus:bg-red-700">Proyectos</a>
          <a href="#" @click.prevent="scrollToSection('contacto')" class="mt-3 sm:mt-0 px-3 py-2 rounded-md text-sm font-medium text-colorwhite hover:text-primary hover:bg-red-700 focus:outline-none focus:text-primary focus:bg-red-700">Contáctame</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
import VueScrollTo from 'vue-scrollto';

export default {
  data() {
    return {
      menuOpen: false
    };
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen;
    },
      scrollToSection(sectionId) {
      VueScrollTo.scrollTo(`#${sectionId}`, 500);
    },
  }
};
</script>

