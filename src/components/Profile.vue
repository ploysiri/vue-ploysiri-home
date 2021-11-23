<template>
  <div class="w3-row ">
    <div class="w3-half w3-container">
      <img
        :src="`https://reg.buu.ac.th/registrar/getstudentimage.asp?id=61160220`"
      />
    </div>
    <h1 class="w3-xxlarge">EDUCATION</h1>
    <p class="w3-text-white">
      <b>2018 - present </b><br>
      Burapha University B.Sc.(Information Technology) - in progress Faculty of Informatics<br> 
      <b>2012 - 2017</b><br>
      Suansriwittaya School<br>
      English-Mathematics
    </p>
    </div>
  </div>

  <div class="w3-row">
    <div class="w3-half w3-container">
      <h1 class="w3-xxlarge">MISS PLOYSIRI KADUN</h1>
      <p class="w3-text-white">
         Hello, my name is Ploysiri Kadun, My nickname Ploy <br />
         My birthday is the 30th of December 1999, now I'm 21 years old. <br />
      </p>
    </div>
    <h1 class="w3-xxlarge">COMPUTER SKILLS</h1>
    <p class="w3-text-white">
      <b><i class='fas fa-angle-right'>  Programming lang : </i></b>
       HTML, Java, R, Linux, laravel<br />
       <b><i class='fas fa-angle-right'>  Tool  : </i></b>
       Eclipse Java, Vs Code, Github, R, studio, GNU Octave<br />
       <b><i class='fas fa-angle-right'>  Software : </i></b>
       Microsoft Word, Microsoft Windows, Microsoft Excel, Microsoft Power Point,
       Photoshop, MySQL, Workbench 8.0 CE
    </p>
  </div>

  <div class="w3-row">
    <div class="w3-half w3-container">
      <h1 class="w3-xxlarge">CAREER OVERVIEW</h1>
      <p class="w3-text-white">
         To be part of organization that provides me a challenging <br />
         job which helps me achieve personal as well as organizational goals.
      </p>
    </div>
    <h1 class="w3-xxlarge">CERTIFICATION</h1>
    <p class="w3-text-white">
      Mikrotik mtcna
    </p>
  </div>

  <router-link :to="{ name: 'contact'}">
    <button>CONTACT</button>
  </router-link>

</template>

<script>
export default {
  name: "Profile",
};
</script>

<style>

</style>
