<template>
  <div>
    <h1 class="text-2xl sm:text-3xl text-center mt-20 mb-12 text-colorwhite">
      Construyamos algo <span class="text-primary">increíble</span>
    </h1>
    <form action="" method="post" class="px-4 md:px-36">
      <section class="grid grid-cols-2 gap-3 my-4">
        <input
          class="bg-secundary text-colorwhite rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary"
          placeholder="Nombre completo"
          type="text"
        />
        <input
          class="bg-secundary text-colorwhite rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary"
          placeholder="Dirección de email."
          type="text"
        />
        <input
          class="bg-secundary text-colorwhite rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary"
          placeholder="No. Celular"
          type="text"
        />
        <input
          class="bg-secundary text-colorwhite rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary"
          placeholder="Asunto del email"
          type="text"
        />
      </section>
      <section>
        <textarea
          class="bg-secundary text-colorwhite rounded-md px-4 py-2 focus:outline-none focus:ring-2 focus:ring-primary w-full h-52 resize-none"
          placeholder="Mensaje"
        ></textarea>
      </section>
      <section class="flex justify-center">
        <button class="rounded-lg border-black py-2 px-5 my-4 bg-primary">
          Contactame
        </button>
      </section>
    </form>
  </div>
</template>