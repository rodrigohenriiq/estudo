<template>
  <div>
    <!--######MENU#######-->
    <header>
      <nav
        class="px-32 w-auto h-16 flex items-center text-center bg-gradient-to-b from-white via-white via-80% sticky top-0"
      >
        <div class="flex items-center mr-5">
          <img
            src="https://logos-download.com/wp-content/uploads/2016/10/Shopify_logo_icon.png"
            alt="Shopify Logo"
            class="h-8 w-8"
          />
          <strong>Shopify</strong>
        </div>
        <div class="ml-4 flex flex-grow">
          <ul class="flex space-x-5">
            <li><a href="#solutions">Solutions</a></li>
            <li><a href="#pricing">Pricing</a></li>
            <li><a href="#resources">Resources</a></li>
          </ul>
        </div>
        <div>
          <button>Login</button>
          <button class="bg-black rounded-full text-white h-10 w-32 ml-5">
            Start free trial
          </button>
        </div>
      </nav>
    </header>
    <main>
        <!--######TOPO COM DUAS COLUNAS#######-->
      <div
        class="bg-gradient-to-bl from-cyan-500 from-10% via-teal-300 to-white to-90% h-screen px-32 grid grid-cols-2 space-x-60"
      >
      <!--######COLUNA 1#######-->
        <div class="pt-16 w-10/12">
          <button class="border rounded-full p-2 flex items-center">
            <span class="material-symbols-outlined mr-4">play_arrow</span>Watch
            a 2 min Shopify overview
          </button>
          <div class="my-5 space-y-5 font-extrabold">
            <h1 class="text-7xl">The globall</h1>
            <h1 class="text-7xl">commerce</h1>
            <h1 class="text-7xl">platform</h1>
          </div>
          <h2 class="text-xl my-12">
            Build your business with Shopify to sell online, offline, and
            everywhere in between.
          </h2>
          <form class="bg-white rounded-full flex border py-3 px-3">
            <input
              type="email"
              name="email"
              id="email"
              placeholder="Enter your email address"
              class="h-12 w-auto rounded-full px-3 flex-grow"
            />
            <button
              type="submit"
              class="h-12 w-40 bg-black text-white rounded-3xl"
            >
              Start free trial
            </button>
          </form>
        </div>
        <!--######COLUNA 2#######-->
        <div class="w-8/12 grid grid-cols-2 grid-rows-2 gap-x-8 gap-y-0">
          <img
            src="https://source.unsplash.com/random"
            alt="Random Image 1"
            class="rounded-xl"
          />
          <img
            src="https://source.unsplash.com/random"
            alt="Random Image 2"
            class="rounded-xl"
          />
          <div class="bg-white rounded-xl flex h-24 items-center">
            <img
              src="https://source.unsplash.com/random"
              alt=""
              class="rounded-xl w-20 h-20"
            />
            Teste
          </div>

          <div class="bg-white rounded-xl flex h-24 items-center">
            <img
              src="https://source.unsplash.com/random"
              alt=""
              class="rounded-xl w-20 h-20"
            />
            Segund Teste
          </div>
        </div>
      </div>
    </main>
  </div>
</template>
