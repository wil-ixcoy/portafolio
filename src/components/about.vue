<template>
  <div class="bg-secundary">
    <section
      class="grid grid-cols-1 sm:grid-cols-2 gap-2 mt-4 py-5 px-4 sm:px-12 sm:px-24"
    >
      <article class="flex justify-center items-center">
        <img src="../assets/fotoperfil.png" alt="" />
      </article>
      <section class="">
        <h1
          class="text-center sm:text-left text-4xl lg:text-5xl mt-7 text-colorwhite mb-4"
        >
          Sobre <i class="text-primary">mí</i>
        </h1>

        <p class="text-left text-colorwhite text-lg">
          Soy un desarrollador Full-Stack apasionado por la construcción de
          aplicaciones web y el aprendizaje de nuevas tecnologías. Me encanta
          compartir lo que aprendo y explorar temas nuevos.
        </p>
        <br />

        <p class="text-left text-colorwhite text-lg">
          Además, disfruto trabajar en proyectos que brinden una experiencia de
          usuario inmersiva y atractiva a través del desarrollo eficiente de
          sitios web y aplicaciones web.
        </p>
      </section>
    </section>
  </div>
</template>

<style scoped>
img {
  width: 400px;
  height: 400px;
}
@media (max-width: 640px) {
  img {
    width: 200px;
    height: 200px;
  }
}
</style>