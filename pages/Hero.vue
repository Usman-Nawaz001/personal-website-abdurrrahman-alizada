<template>
    <div class="container px-5 hero ">
  <section class="body-font">
  <div class="mx-auto flex py-24 md:flex-row flex-col ">
    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium">Hi, there
        <br class="hidden lg:inline-block">I'm Usman Nawaz
      </h1>
      <h4 class="title-font sm:text-2xl text-2xl mb-2 font-medium">Developer - Problem Solver - Contributor</h4>
      <p class="mb-8 leading-relaxed">I am pursuing bachelors degree in Computer Software Engineering. I love to play with mathematical models and machine learning models. Also contributing to an open-source community is also on my front desk.</p>
    
      <div class="flex mt-4 bg-purple-100">
      <a href="https://drive.google.com/file/d/1SmLO3AoS6CI_ATNT3niQL_NLq2axyA1J/view?usp=drivesdk" download="resume.pdf" class="text-white bg-purple-900 border-0 py-2 px-4 focus:outline-none hover:bg-purple-900 py-2 px-4 rounded inline-flex items-center">
        <span>Download Resume</span>
        <svg class="w-4 h-4 ml-2" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M9 19l3 3m0 0l3-3m-3 3V10" />
        </svg>
      </a>

        <nuxt-link to="/Contact" class="ml-4 inline-flex text-white bg-yellow-500 text-gray-900 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-800 rounded text-lg">Contact me</nuxt-link>
      </div>
    </div>
    <div class="lg:max-w-lg bg-purple-100 lg:w-full mt-5 md:w-1/2 w-5/6">
      <img class="object-cover object-center h-20 w-20 rounded -m-5 animate-bounce" alt="hero" src="@/assets/svgs/b.svg">
      <img class="object-cover object-center rounded" alt="hero" src="@/assets/svgs/2.svg">

    </div>
  </div>
</section>
    </div>
</template>


<script>
export default{
  data(){
    return{
      resume : '@/static/resume.pdf'
    }
  }
}
</script>


<style scoped>
.hero{
    font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  color: #35495e;
  letter-spacing: 1px;

}
</style>