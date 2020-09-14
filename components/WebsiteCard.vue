<template>    

  <div class="m-10 flex">
    
    <nuxt-link :to="to_page"><slot></slot></nuxt-link>

    <div class="ml-2 flex flex-col justify-center">

      <nuxt-link :to="to_page"><h3 class="text-xl text-gray-900 hover:text-gray-700 font-bold font-sans antialiased">{{site_name}}</h3></nuxt-link>

      <a :href="to_github"><h3 class="text-gray-700 font-roboto hover:text-gray-600">Github Repo</h3></a>

    </div>
  </div>

</template>  

<script>
	export default {

		props: ['to_page', 'to_github', 'site_name'],
	}
</script>