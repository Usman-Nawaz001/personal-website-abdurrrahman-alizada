<template>
    <div class="">
        <section class="text-gray-600 body-font mt-5 container">
         <h1 class="font-bold heading text-4xl font-black flex items-center justify-center">Projects I worked on!</h1>
         <div class="container px-5 mx-auto">
    <div class="flex flex-wrap">
<div class="container flex mx-auto px-4 md:px-12">
<div class="flex">
 <img class="" src="@/assets/svgs/github.svg"/>
  </div> 
   <span class="font-bold mt-10 p-10 self-center">
         <h4 class="font-bold text-xl font-black items-center justify-center self-center">Here are some of my latest projects, which I am working on or already worked. Also check out my github account for more info.</h4> 
   <a href="https://github.com/Usman-Nawaz001" target="_blank" class="title-font flex items-center sm:text-4xl text-3xl font-medium">
  GitHub
   <svg class="h-10 w-10 animate-ping" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 9l3 3m0 0l-3 3m3-3H8m13 0a9 9 0 11-18 0 9 9 0 0118 0z" />
</svg>
   </a>
 </span>
</div>
    </div>
  </div>


  <section class="text-gray-600 body-font overflow-hidden">
  <div class="container px-5 py-24 mx-auto">
    <div class="-my-8 divide-y-2 divide-gray-100">
      <div class="py-8 flex flex-wrap md:flex-nowrap">
        <div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
          <span class="mt-1 text-gray-500 text-sm">October 2020 - Now</span>
        </div>
        <div class="md:flex-grow">
          <h2 class="text-2xl font-medium text-gray-900 title-font mb-2">U-Safety</h2>
          <p class="leading-relaxed">An android based app, which helps users to maintain their privacy irrespective of using differnet social media sites. Also, it will provide assistance to users that they can check their daily traffic usage on their network. Also, it informs users about differnet kinds of malicious attacks done on their device.</p>
         
        </div>
      </div>
      <div class="py-8 flex flex-wrap md:flex-nowrap">
        <div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
          <span class="mt-1 text-gray-500 text-sm">June 2020 - November 2020</span>
        </div>
        <div class="md:flex-grow">
          <h2 class="text-2xl font-medium text-gray-900 title-font mb-2">Behavidence</h2>
          <p class="leading-relaxed">Behavidence was founded to help people with the diagnosis, monitoring and therapy of mental health conditions. Utilizing digital phenotyping and machine learning algorithm we aim to give the app users, care givers and clinical therapists high accuracy tools to evaluate onset, progression and relapse of mental health conditions together with signals, data-driven insights and technology to improve and enhance therapies and quality of life.</p>

        </div>
      </div>
    </div>
  </div>
</section>
        </section>
    </div>
    
</template>

<script>

export default{

  data(){
    return{
      projects : [
        {
        title : 'Lara-Start',
        desc  : 'It is multiuser Blog website built in Vue and laravel',
        link  : 'https://github.com/Abdurrahman-Alizada/lara-start',
        avatar: require('@/assets/svgs/lav.svg')
        },

        {
        title : 'Book Store Management system 2',
        desc  : 'It was my first project which can maintain all necessary actions for a book store. Developed in Laravel and Vue.js.',
        link  : 'https://github.com/Abdurrahman-Alizada/bookStoreManagementSystem',
         avatar: require('@/assets/svgs/lav.svg')
        },

        {
        title : 'React Quiz',
        desc  : 'React MCQs type Quiz website. which is taking data from an API. Built in React',
        link  : 'https://github.com/Abdurrahman-Alizada/react-quiz',
            avatar: require('@/assets/svgs/react.svg')

        },

      ],
    }
  }
}
</script>

<style scoped>
 .heading{
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
