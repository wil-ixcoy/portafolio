<script setup>
</script>

<template>
  <section class="grid sm:grid-cols-1 md:grid-cols-2 gap-10 mx-auto">
    <article class="sm:p-10">
      <h1
        class="text-center md:text-left text-colorwhite text-3xl md:text-4xl lg:text-5xl"
      >
        Hola, soy Wiliams
      </h1>
      <p
        class="text-center md:text-left text-colorwhite text-xl lg:text-2xl pt-3"
      >
        Backend y frontend developer.
      </p>

      <section
        class="grid grid-cols-4 gap-3 my-4 mx-2 text-center sm:text-left"
      >
        <a
          target="_blank"
          href="https://github.com/wil-ixcoy"
          class="text-2xl text-primary"
        >
          <i class="fab fa-github"></i>
        </a>
        <a
          target="_blank"
          href="https://www.linkedin.com/in/wiliamsixcoy/"
          class="text-2xl text-primary"
        >
          <i class="fab fa-linkedin"></i>
        </a>
        <a
          target="_blank"
          href="https://www.instagram.com/wil_ixcoy/"
          class="text-2xl text-primary"
        >
          <i class="fab fa-instagram"></i>
        </a>
        <a
          target="_blank"
          href="https://twitter.com/wil_ixcoy"
          class="text-2xl text-primary"
        >
          <i class="fab fa-twitter"></i>
        </a>
      </section>

<button class="rounded-lg border-black py-2 px-5 my-4 bg-primary mx-24 sm:ml-auto sm:mr-0">
  Contactame
</button>

    </article>
    <article class="flex justify-center items-center">
      <img src="../assets/fotoperfil.png" alt="" />
    </article>
  </section>
</template>

<style scoped>
img {
  width: 400px;
  height: 400px;
}
@media (max-width: 640px) {
  img {
    width: 300px;
    height: 300px;
  }
}
</style>