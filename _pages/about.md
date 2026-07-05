---
permalink: /
title: "Hello"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- START AUTOMATIC SLIDESHOW CAROUSEL -->
<div class="slider-container" style="position: relative; width: 100%; height: 350px; max-height: 40vh; overflow: hidden; border-radius: 8px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
  
  <!-- Slide 1 -->
  <div class="mySlides fade-anim" style="position: absolute; width: 100%; height: 100%;">
    <img src="/images/banner1.jpg" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

  <!-- Slide 2 -->
  <div class="mySlides fade-anim" style="position: absolute; width: 100%; height: 100%;">
    <img src="/images/banner2.jpg" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

  <!-- Slide 3 -->
  <div class="mySlides fade-anim" style="position: absolute; width: 100%; height: 100%;">
    <img src="/images/banner3.jpg" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

</div>

<!-- CSS Animations & JavaScript Driver Code -->
<style>
  .fade-anim {
    animation: fadeEffect 1.5s ease-in-out;
  }
  @keyframes fadeEffect {
    from { opacity: 0.4; } 
    to { opacity: 1; }
  }
</style>

<script>
  let slideIndex = 0;
  function showSlides() {
    let slides = document.getElementsByClassName("mySlides");
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}    
    if (slides[slideIndex-1]) {
      slides[slideIndex-1].style.display = "block";  
    }
    setTimeout(showSlides, 4000); // Changes image automatically every 4 seconds
  }
  // Run once page elements construct completely
  document.addEventListener("DOMContentLoaded", showSlides);
  // Fail-safe trigger if cache loads fast
  setTimeout(function() { if(document.getElementsByClassName("mySlides")[0]?.style.display === "none" && slideIndex === 0) showSlides(); }, 500);
</script>
<!-- END AUTOMATIC SLIDESHOW CAROUSEL -->


I'm Lok Cheuk Fung. I usually go by Charles.

I'm a linguist, but sometimes I'm not sure if I can call myself one yet (what even are the criteria, anyway?) Hopefully one day I can say it out loud with real confidence. I'm working towards that every day.

<div style="background-color: #e6f2f7; border-radius: 6px; padding: 15px; margin: 20px 0;">

<strong>What's new?</strong>

<ul style="margin-top: 10px; padding-left: 20px;">
  <li>Starting from Aug 2026, I'll be a Research Masters student at the <a href="https://fass.nus.edu.sg/elts/" target="_blank">Department of English, Linguistics and Theatre Studies, National University of Singapore</a>.</li>
  <li>My first paper is published! Check it out <a href="https://journals.sagepub.com/doi/10.1177/13670069251405684?__cf_chl_f_tk=Je3JD2ZHiBOg7c9O6bh63WbOnQCBEsK8cOReGBP1sG0-1782993785-1.0.1.1-UApkNu_rpjJBdzZnfs0r2aIh2LHxrehZVQcjvYDbH5E" target="_blank">here</a>.</li>
</ul>

</div>

