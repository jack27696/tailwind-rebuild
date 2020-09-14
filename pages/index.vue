<template>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TailwindCSS Rebuilds | Home</title>
</head>
<body class="bg-gray-300">
  <div class="flex flex-col min-h-screen border-t-8 border-teal-500"> 
    
    <header class="flex flex-col items-center m-10 min-h-10">

      <TailwindcssLogo class="bg-image" />

      <div class="flex flex-col items-center">
        <h1 class="text-3xl text-gray-900 font-bold font-sans antialiased text-center">TailwindCSS Site Rebuilds</h1>
        <h6 class="text-lg text-gray-700 font-roboto">Built using <a class="underline hover:text-gray-800" href="#">Tailwind V.1.8.3</a></h6>
      </div>

    </header>

    <main class="my-6 flex flex-wrap self-center justify-center max-w-xl md:max-w-3xl lg:max-w-none">


      <WebsiteCard 
        to_page="google"
        to_github="https://github.com/jack27696/tailwind-rebuild/blob/master/pages/google.vue"
        site_name="Google">

        <GoogleLogo />

      </WebsiteCard>


      <WebsiteCard 
        to_page="github"
        to_github="https://github.com/jack27696/tailwind-rebuild/blob/master/pages/github.vue"
        site_name="Google">

        <GithubLogo />

      </WebsiteCard>

      <WebsiteCard 
        to_page="disney"
        to_github="https://github.com/jack27696/tailwind-rebuild/blob/master/pages/disney.vue"
        site_name="Disney+">

        <DisneyLogo />

      </WebsiteCard>

        

    </main>

    <div class="flex-grow spacer"></div>

    <footer class="flex flex-col my-10 text-gray-700 font-roboto w-full items-center">
      <div>Made by Jack Edwards</div>
      <div>Heavily Inspired by Andre Madarang · <a class="underline hover:text-gray-800" href="https://twitter.com/drehimself?lang=en">@drehimself</a>  - Please check out his work! <a href="https://github.com/drehimself" class="inline-block"><GithubLogoNoBG /></a> </div>
    </footer>

  </div>
  </body>
</html>
</template>


<script>

export default {

      
}
</script>

<style>

</style>
