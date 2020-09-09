<template>
  <div class="flex flex-col bg-gray-300 h-screen w-screen justify-center items-center border-t-8 border-teal-500"> 

    <header class="flex flex-col content-center items-center">

      <TailwindcssLogo />

      <div class="flex flex-col items-center">
        <h1 class="text-3xl text-gray-900 font-bold font-sans antialiased">TailwindCSS Site Rebuilds</h1>
        <h6 class="text-lg text-gray-700 font-roboto">Built using <a class="underline hover:text-gray-800" href="#">Tailwind V.1.8.3</a></h6>
      </div>

    </header>

    <main class="my-6 flex">

      <div class="m-4 flex">
        <nuxt-link to="google"><GoogleLogo class="mr-2" /></nuxt-link>
        <div class="ml-2 flex items-center">

          <nuxt-link to="google"><h3 class="text-lg text-gray-900 hover:text-gray-700 font-bold font-sans antialiased">Google</h3></nuxt-link>

        </div>
      </div></nuxt-link>

      <nuxt-link to="github"><div class="m-4 flex">
        <GithubLogo />
        <div><h3></h3></div>
      </div></nuxt-link>
        

    </main>

    <footer class="flex flex-col text-gray-700 font-roboto">
      <div>Made by Jack Edwards</div>
      <div>Heavily Inspired by Andre Madarang · <a class="underline hover:text-gray-800" href="https://twitter.com/drehimself?lang=en">@drehimself</a>  - Please check out his work! <a href="https://github.com/drehimself" class="inline-block"><GithubLogoNoBG /></a> </div>

      <div>
        
      </div>

    </footer>

  </div>
</template>

<script>
export default {
      
}
</script>

<style>

</style>
