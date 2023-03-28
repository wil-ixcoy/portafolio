<template>
  <div>
    <h1 class="text-4xl mt-12 text-colorwhite">Mis Proyectos</h1>
    <h2 class="text-3xl text-left text-primary">Proyectos Frontend:</h2>

    <section class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 2xl:grid-cols-5 gap-4">
      <!-- primer proyecto Weather App -->
      <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
        <img
          src="https://picsum.photos/200/300"
          alt=""
          class="w-full h-28 rounded-t-md"
        />
        <div class="p-3">
          <h3 class="text-primary text-xl text-left">Weather App</h3>
          <p class="text-colorwhite text-left">
            Weather app es una web interactiva que muestra datos meteorológicos
            de distintas ciudades del mundo. Solo tienes que buscar la ciudad
            que desees.
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

    <!-- proyectos backend developer -->
    <h2 class="text-3xl text-left text-primary mt-12">Proyectos Backend:</h2>

    <section class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 2xl:grid-cols-5 gap-4">
      <!-- primer proyecto clon de pinterest-->
      <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
        <img
          src="https://picsum.photos/200/300"
          alt=""
          class="w-full h-28 rounded-t-md"
        />
        <div class="p-3">
          <h3 class="text-primary text-xl text-left">Clon de Pinterest</h3>
          <p class="text-colorwhite text-left">
            Es una app realizada con el fin de poder mejorar mis habilidades de
            programación del lado del backend. Uso de multer para la subida de
            imagénes, cloudinary para almacenamiento.
          </p>

          <section class="grid grid-cols-5 gap-3 my-4 px-3">
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/nodejs-icon.svg"
              alt="nodejs"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/sequelize.svg"
              alt=""
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/postgresql.svg"
              alt="postgresql"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/javascript.svg"
              alt="js"
            />

            <img
              class="w-7 h-7"
              src="../assets/tecnologias/docker-icon.svg"
              alt="docker"
            />
          </section>

          <div class="flex justify-between mt-5 px-8">
            <button
              class="bg-primary rounded py-2 px-4"
              onclick="window.open('https://github.com/wil-ixcoy/Pinterest_Clon')"
            >
              GitHub
            </button>
            <button
              class="text-colorwhite border-primary rounded py-2 px-4"
              onclick="window.open('https://pinterestclon-production.up.railway.app/api/docs/')"
            >
              Demo
            </button>
          </div>
        </div>
      </section>

      <!-- segundo proyecto Draux API-->
      <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
        <img
          src="https://picsum.photos/200/300"
          alt=""
          class="w-full h-28 rounded-t-md"
        />
        <div class="p-3">
          <h3 class="text-primary text-xl text-left">DRAUX API</h3>
          <p class="text-colorwhite text-left">
            Draux es una plataforma web destinada a conectar a profesionales y
            aficionados del diseño UX. Ofrece un espacio para que los usuarios
            compartan contenido relacionado con el diseño UX.
          </p>

          <section class="grid grid-cols-5 gap-3 my-4 px-3">
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/nodejs-icon.svg"
              alt="nodejs"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/sequelize.svg"
              alt=""
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/postgresql.svg"
              alt="postgresql"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/javascript.svg"
              alt="js"
            />

            <img
              class="w-7 h-7"
              src="../assets/tecnologias/docker-icon.svg"
              alt="docker"
            />
          </section>

          <div class="flex justify-between mt-5 px-8">
            <button
              class="bg-primary rounded py-2 px-4"
              onclick="window.open('https://github.com/wil-ixcoy/Draux')"
            >
              GitHub
            </button>
            <button
              class="text-colorwhite border-primary rounded py-2 px-4"
              onclick="window.open('https://draux-production.up.railway.app/api/v1/docs/')"
            >
              Demo
            </button>
          </div>
        </div>
      </section>
      <!-- tercer proyecto Playit-->
      <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
        <img
          src="https://picsum.photos/200/300"
          alt=""
          class="w-full h-28 rounded-t-md"
        />
        <div class="p-3">
          <h3 class="text-primary text-xl text-left">Platzi Store</h3>
          <p class="text-colorwhite text-left">
            latzi Store es una aplicación desarrollada con Node.js para
            construir una tienda de venta de productos. A continuación detallo
            la ruta de cursos que hemos seguido para desarrollar esta
            aplicación.
          </p>

          <section class="grid grid-cols-5 gap-3 my-4 px-3">
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/nodejs-icon.svg"
              alt="nodejs"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/sequelize.svg"
              alt=""
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/postgresql.svg"
              alt="postgresql"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/javascript.svg"
              alt="js"
            />

            <img
              class="w-7 h-7"
              src="../assets/tecnologias/docker-icon.svg"
              alt="docker"
            />
          </section>

          <div class="mt-5 px-8">
            <button
              class="bg-primary rounded py-2 px-4"
              onclick="window.open('https://github.com/wil-ixcoy/myStore-nodeExpress')"
            >
              GitHub
            </button>
          </div>
        </div>
      </section>

      <!-- primer proyecto Telegram Bot-->
      <section class="bg-secundary rounded-md drop-shadow-2xl mt-6">
        <img
          src="https://picsum.photos/200/300"
          alt=""
          class="w-full h-28 rounded-t-md"
        />
        <div class="p-3">
          <h3 class="text-primary text-xl text-left">Bot de Telegram</h3>
          <p class="text-colorwhite text-left">
            Bot de telegram, cuya función principal es poder mostrar en tiempo
            real el clima de las distintas ciudades del mundo, solo tienes que
            escribir el nombre de la ciudad que deseas consultar.
          </p>

          <section class="grid grid-cols-3 gap-3 my-4 px-3">
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/nodejs-icon.svg"
              alt="nodejs"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/javascript.svg"
              alt="js"
            />
            <img
              class="w-7 h-7"
              src="../assets/tecnologias/axios.svg"
              alt="axios"
            />
          </section>

          <div class="flex justify-between mt-5 px-8">
            <button
              class="bg-primary rounded py-2 px-4"
              onclick="window.open('https://github.com/wil-ixcoy/telegram_Bot')"
            >
              GitHub
            </button>
            <button
              class="text-colorwhite border-primary rounded py-2 px-4"
              onclick="window.open('https://t.me/weatherByWiliams_bot')"
            >
              Demo
            </button>
          </div>
        </div>
      </section>
    </section>
  </div>
</template>
