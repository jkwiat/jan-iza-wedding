---
layout: landing
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Dancing+Script:wght@600&family=EB+Garamond:ital,wght@0,500;1,500&display=swap');

  #banner h2 {
      font-family: "Abril Fatface", serif;
      font-weight: 400;
      font-style: normal; 
  }
  /* @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&display=swap');
  
  #banner h2 {
    font-family: "Dancing Script", cursive;
    font-optical-sizing: auto;
    font-weight: 600;
    font-style: normal;
  } */
 </style>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=EB+Garamond:ital,wght@0,500;1,500&display=swap');

  #banner p {
    font-family: "EB Garamond", serif;
    font-optical-sizing: auto;
    font-weight: 500;
    font-style: normal;
  }
</style>

<section id="banner">
  <div class="inner">
    <h2>{{ site.title }}</h2>
    <p>{{ site.description | markdownify }}</p>
  </div>
  <a href="#intro" class="more scrolly">Szczegóły</a>
</section>

<section id="details" class="wrapper style1 special">
  {% include sections/details.html %}
</section>

<section id="couple" class="wrapper alt style2">
{% include sections/couple.html %}
</section>

<section id="dworafrodyta" class="wrapper alt style2">
{% include sections/dworafrodyta.html %}
</section>