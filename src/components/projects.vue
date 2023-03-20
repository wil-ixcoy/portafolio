<template>
  <h1 class="text-4xl mt-12 text-colorwhite">Mis Proyectos</h1>
  <h2 class="text-3xl text-left text-primary">Proyectos Frontend:</h2>

  <!-- primer proyecto Weather App -->
  <section class="grid grid-cols-4 gap-4">
    <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
      <img
        src="https://picsum.photos/200/300"
        alt=""
        class="w-full h-28 rounded-t-md"
      />
      <div class="p-3">
        <h3 class="text-primary text-xl text-left">Weather App</h3>
        <p class="text-colorwhite text-left">
          Weather app es una web interactiva que muestra datos meteorológicos de
          distintas ciudades del mundo. Solo tienes que buscar la ciudad que
          desees.
        </p>

        <section class="grid grid-cols-4 gap-3 my-4 px-3">
          <img class="w-7 h-7" src="../assets/tecnologias/axios.svg" alt="" />
          <img class="w-7 h-7" src="../assets/tecnologias/sass.svg" alt="" />
          <img
            class="w-7 h-7"
            src="../assets/tecnologias/javascript.svg"
            alt=""
          />
          <img class="w-7 h-7" src="../assets/tecnologias/vue.svg" alt="" />
        </section>

        <div class="flex justify-between mt-5 px-8">
          <button
            class="bg-primary rounded py-2 px-4"
            onclick="window.open('https://github.com/wil-ixcoy/Weather')"
          >
            GitHub
          </button>
          <button
            class="text-colorwhite border-primary rounded py-2 px-4"
            onclick="window.open('https://jolly-dubinsky-4b78aa.netlify.app/#/')"
          >
            Demo
          </button>
        </div>
      </div>
    </section>

    <!-- segundo proyecto iQuela-->
    <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
      <img
        src="https://picsum.photos/200/300"
        alt=""
        class="w-full h-28 rounded-t-md"
      />
      <div class="p-3">
        <h3 class="text-primary text-xl text-left">iQuela</h3>
        <p class="text-colorwhite text-left">
          iQuela es una plataforma de educación online que busca que los
          estudiantes pongan en práctica sus conocimientos con proyectos
          similares a la realidad laboral.
        </p>

        <section class="grid grid-cols-4 gap-3 my-4 px-3">
          <img
            class="w-7 h-7"
            src="../assets/tecnologias/firebase.svg"
            alt=""
          />
          <img class="w-7 h-7" src="../assets/tecnologias/sass.svg" alt="" />
          <img
            class="w-7 h-7"
            src="../assets/tecnologias/javascript.svg"
            alt=""
          />
          <img class="w-7 h-7" src="../assets/tecnologias/vue.svg" alt="" />
        </section>

        <div class="mt-5 px-12">
          <!--  <button
            class="bg-primary rounded py-2 px-4"
            onclick="window.open('https://github.com/wil-ixcoy/Weather')"
          >
            GitHub
          </button> -->
          <button
            class="text-colorwhite border-primary rounded py-2 px-8"
            onclick="window.open('https://iquela.web.app/')"
          >
            Demo
          </button>
        </div>
      </div>
    </section>

    <!-- segundo proyecto Registro iQuela-->
    <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
      <img
        src="https://picsum.photos/200/300"
        alt=""
        class="w-full h-28 rounded-t-md"
      />
      <div class="p-3">
        <h3 class="text-primary text-xl text-left">Registro iQuela</h3>
        <p class="text-colorwhite text-left">
          iQuela Registro es un proyecto que permite a los usuarios
          registrarse y recibir notificaciones sobre el avance de iQuela.
          Siendo los primeros en poder probar la nueva solución.
        </p>

        <section class="grid grid-cols-4 gap-3 my-4 px-3">
          <img
            class="w-7 h-7"
            src="../assets/tecnologias/firebase.svg"
            alt=""
          />
          <img class="w-7 h-7" src="../assets/tecnologias/css-3.svg" alt="" />
          <img
            class="w-7 h-7"
            src="../assets/tecnologias/javascript.svg"
            alt=""
          />
          <img class="w-7 h-7" src="../assets/tecnologias/vue.svg" alt="" />
        </section>

        <div class="mt-5 px-12">
          <!--  <button
            class="bg-primary rounded py-2 px-4"
            onclick="window.open('https://github.com/wil-ixcoy/Weather')"
          >
            GitHub
          </button> -->
          <button
            class="text-colorwhite border-primary rounded py-2 px-8"
            onclick="window.open('https://iquela-registro.web.app/')"
          >
            Demo
          </button>
        </div>
      </div>
    </section>
  </section>
</template>
