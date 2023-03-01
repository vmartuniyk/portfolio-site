<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16 mt-8">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Volodimir Martuniyk </div>
        <div class="text-indigo-500 leading-tight">Laravel developer</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/developer.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">Hello! I’m Volodimir. I spend my days developing web applications. I specialize in the Laravel PHP framework on the backend, Vue.js on frontend and SASS for styling. I also love being involved in development OpenSource projects</p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/financial_data.svg" alt="browser" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/code_review.svg" alt="mobile" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div id="projects" style="position: relative; top: -40px; left: 0"/>
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="checkmark">
            <div>Tweety</div>
            <div class="text-lg text-gray-600">This is a project copy of the Twitter site where you can, post your own tweets, subscribe to interesting users, edit your profile and much more. <a href="https://github.com/vmartuniyk/mini-twitter" target="_blank">GitHub Link</a></div>
          </li>
          <li class="checkmark">
            <div>Video Games site</div>
            <div class="text-lg text-gray-600">This application built in Laravel that uses the IGDB API to display some game informations. This project uses HTTP client, Tailwind CSS, Livewire and Alpine.js <a href="https://github.com/vmartuniyk/video-games" target="_blank">GitHub Link</a> or <a href="https://video-games.vercel.app/" target="_blank">Live Link</a></div>
          </li>
          <li class="checkmark">
            <div>Book space | Book challenge </div>
            <div class="text-lg text-gray-600">My author's project.This is a book challenge that lasted 3 weeks. Each participant had to choose 1 book to read it and write a review about the book. This adds extra motivation and encourages the habit of reading every day  <a href="https://github.com/vmartuniyk/recenzia" target="_blank">GitHub Link</a> or <a href="https://bookspace.netlify.app" target="_blank">Live Link</a> </div>
          </li>
          <li class="checkmark">
            <div>Lace of travel</div>
            <div class="text-lg text-gray-600">A site for a travel company where I developed frontend (HTML and CSS) and backend(Laravel) <a href="https://merezhyvo-mandriv.com.ua/" target="_blank">Live Link</a></div>
          </li>

        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div id="about" style="position: relative; top: -40px; left: 0"/>
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <h2 class="font-bold mb-6">Get to know me:</h2>

        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/avatar.jpg" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">I love to write the code and actively spend time on the journeys and discover new routes for running.</div>
        </div>
      </div> <!-- end get-to-know me -->
    </div>

    <div class="overflow-x-hidden">
      <div id="contact" style="position: relative; top: -40px; left: 0"/>
      <div class="contact-me bg-background-secondary pt-16">
        <div class="container-inner mx-auto text-xl pb-4 relative">
          <h2 class="font-bold mb-6">Contact me:</h2>

          <div class="absolute right-0 top-0" style="transform: translate(100%) rotate(180deg)">
            <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
          </div>

          <p class="mb-12">If you’re looking to get in contact with me for business inquiries or if you have a question, feel free to <a href="mailto:volodimir.martuniyk@gmail.com">email me.</a>  I’ll try to respond as soon as I can. </p>

          <div class="text-lg sm:text-lg mb-16">
         
          </div>
        </div>
      </div> <!-- end contact-me -->
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Home'
  }
}
</script>
