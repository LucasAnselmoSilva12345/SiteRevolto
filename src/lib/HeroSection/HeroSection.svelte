<script>
  import Header from '../Header/Header.svelte';
</script>

<Header />
<section class="bg-zinc-900">
  <div class="container px-6 py-16 mx-auto text-center">
    <div class="max-w-4xl mx-auto">
      <h1 class="text-3xl font-bold text-white lg:text-7xl">
        Eu não escolhi ser gamer, foi essa vida que me escolheu.
      </h1>
      <p class="mt-6 text-slate-400">
        Sou gamer e não tenho paciência para quem se acha melhor que os outros
        porque tem equipamentos mais caros
      </p>
      <button
        class="px-6 py-2.5 mt-6 text-sm font-medium leading-5 text-center text-white capitalize bg-red-600 rounded-lg hover:bg-red-500 lg:mx-0 lg:w-auto lg:text-base focus:outline-none"
      >
        Bora jogar
      </button>
    </div>

    <div class="flex justify-center mt-10">
      <img
        class="object-cover w-full h-96 rounded-xl lg:w-4/5"
        src="https://images.unsplash.com/photo-1582731595896-f959c4fb1509?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=786&q=80"
      />
    </div>
  </div>
</section>
