---
permalink: /
title: "Hello"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

header:
  actions:
    - html: |
        <div class="top-slider" style="position: relative; width: 100vw; margin-left: calc(-50vw + 50%); height: 380px; overflow: hidden; background: #000;">
          <div class="topSlide fade-in" style="position: absolute; width: 100%; height: 100%; display: block;"><img src="/images/parismonet.jpg" style="width:100%; height:100%; object-fit:cover;"></div>
          <div class="topSlide fade-in" style="position: absolute; width: 100%; height: 100%; display: none;"><img src="/images/hochimingtinhautemple.jpg" style="width:100%; height:100%; object-fit:cover;"></div>
          <div class="topSlide fade-in" style="position: absolute; width: 100%; height: 100%; display: none;"><img src="/images/sevensisterscliff.jpg" style="width:100%; height:100%; object-fit:cover;"></div>
        </div>
        <style>
          .fade-in { animation: headerFade 1.2s ease-in-out; }
          @keyframes headerFade { from { opacity: 0.3; } to { opacity: 1; } }
          /* Ensure the theme's core header wrapper doesn't trap our full-bleed images */
          .page__hero--overlay { padding: 0 !important; margin: 0 !important; background: transparent !important; }
        </style>
        <script>
          (function() {
            let idx = 0;
            function runHeaderCarousel() {
              let arr = document.getElementsByClassName("topSlide");
              if (!arr.length) return;
              for (let i = 0; i < arr.length; i++) arr[i].style.display = "none";
              idx++;
              if (idx > arr.length) idx = 1;
              arr[idx-1].style.display = "block";
              setTimeout(runHeaderCarousel, 4000);
            }
            document.addEventListener("DOMContentLoaded", runHeaderCarousel);
            setTimeout(function() { if(document.getElementsByClassName("topSlide")[0]?.style.display === "none" && idx === 0) runHeaderCarousel(); }, 600);
          })();
        </script>
---

I'm Lok Cheuk Fung. I usually go by Charles.

I'm a linguist, but sometimes I'm not sure if I can call myself one yet (what even are the criteria, anyway?) Hopefully one day I can say it out loud with real confidence. I'm working towards that every day.

<div style="background-color: #e6f2f7; border-radius: 6px; padding: 15px; margin: 20px 0;">

<strong>What's new?</strong>

<ul style="margin-top: 10px; padding-left: 20px;">
  <li>Starting from Aug 2026, I'll be a Research Masters student at the <a href="https://fass.nus.edu.sg/elts/" target="_blank">Department of English, Linguistics and Theatre Studies, National University of Singapore</a>.</li>
  <li>My first paper is published! Check it out <a href="https://journals.sagepub.com/doi/10.1177/13670069251405684?__cf_chl_f_tk=Je3JD2ZHiBOg7c9O6bh63WbOnQCBEsK8cOReGBP1sG0-1782993785-1.0.1.1-UApkNu_rpjJBdzZnfs0r2aIh2LHxrehZVQcjvYDbH5E" target="_blank">here</a>.</li>
</ul>

</div>

