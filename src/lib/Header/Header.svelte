<script>
  import LogoRevolto from '../../assets/RevoltoLogo.png';
</script>

<header class="bg-zinc-900 text-gray-600 body-font">
  <div
    class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center"
  >
    <a
      class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0"
    >
      <img
        class="object-cover w-full h-10 lg:w-full"
        src={LogoRevolto}
        alt="Logo revolto"
      />
    </a>
    <nav
      class="md:ml-auto md:mr-auto flex flex-wrap items-center text-base justify-center"
    >
      <a class="mr-5 text-slate-100">Home</a>
      <a class="mr-5 text-slate-100">Sobre</a>
      <a class="mr-5 text-slate-100">Jogos</a>
      <a class="mr-5 text-slate-100">Contato</a>
    </nav>

    <button
      class="inline-flex items-center bg-red-600 text-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-slate-200 rounded-lg text-base mt-4 md:mt-0"
      >Registrar
    </button>
  </div>
</header>
