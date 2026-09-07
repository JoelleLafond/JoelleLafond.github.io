---
layout: posts
permalink: /About/
author_profile: false
title: '<p class="title-post" > About Me </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner4.jpg
excerpt: '<p class="excerpt-post"> Background, values and hobbies</p>' 
---



<h1> A little background </h1>

<p align="justify">
My fascination with biology has always stemmed from the unexpected. I am particularly drawn to the unusual and intriguing phenomena that challenge our understanding of how life works. It was therefore only natural for me to become interested in atypical reproductive modes, which eventually led me to pursue a PhD focused on the reproduction of the diploid and triploid hybrid fish <i>Chrosomus eos-neogaeus</i>. 
</p>

<img-div>
<img width="600px" src="../assets/images/About5.jpg" class="center" />
<figcaption>Some field work during my PhD</figcaption>
</img-div>


<p align="justify">
My path into academia was not exactly what one would call conventional. I grew up in a rural environment surrounded by forests, wildlife, and nature, which fostered my curiosity about the living world from an early age. Although I always enjoyed science, I was unaware that academic research was even a career option until I began my undergraduate studies.</p>

<p align="justify">
As a first-generation university student from a modest background, navigating higher education often meant learning its unwritten rules on my own. From scholarship applications to graduate studies and academic research, many aspects of the academic world were unfamiliar to me. These experiences taught me resilience, independence, and perseverance, while also highlighting the profound impact that mentors and understanding, supportive communities can have on a student's trajectory. </p>

<p align="justify">
Throughout my career, I have been fortunate to work with outstanding mentors, collaborators, students, and colleagues. Their support has shaped my development as both a researcher and an educator. These experiences have also strengthened my commitment to building a scientific community that is inclusive, supportive, and accessible to individuals from diverse backgrounds and life experiences.
</p>

<p align="justify">
As I develop my own research program, I strive to foster an environment where students can grow scientifically while remaining true to their individual goals, strengths, and aspirations. I believe that effective mentorship requires recognizing that each trainee arrives with a unique background and set of experiences, and that personalized guidance is essential for helping them reach their full potential.
</p>

<div style="margin:0 auto 1rem auto;">
<img class="center" style="Padding: 10px 10px 10px 10px" src="../assets/images/About_all.png"/>
<figcaption>Some places where we went for fish samplings during my PhD</figcaption>
</div>

<p align="justify">
Outside of academia, I remain deeply connected to the natural world that originally inspired my interest in biology. I enjoy wildlife photography, creating nature-inspired artwork, and exploring the remarkable diversity of ecosystems and organisms around us. I also share my home with three very spoiled cats, who ensure that life outside the lab is never boring.
</p>


<!-- Back to top button -->
<button type="button" class="btn btn-danger btn-floating btn-lg" id="btn-back-to-top">
  <i class="fas fa-arrow-up"></i>
</button>

<script>
  // Get the button
  let mybutton = document.getElementById("btn-back-to-top");
  
  // Show the button when scrolling down
  window.onscroll = function () {
    scrollFunction();
  };
  
  function scrollFunction() {
    if (
      document.body.scrollTop > 20 ||
      document.documentElement.scrollTop > 20
    ) {
      mybutton.style.display = "block";
    } else {
      mybutton.style.display = "none";
    }
  }
  
  // Smooth scroll to top over 1.0 seconds
  mybutton.addEventListener("click", backToTop);
  
  function backToTop() {
    const duration = 1000; // 1.0 seconds
    const start = document.documentElement.scrollTop || document.body.scrollTop;
    const startTime = performance.now();
  
    function scrollStep(currentTime) {
      const elapsed = currentTime - startTime;
      const progress = Math.min(elapsed / duration, 1); // clamp 0–1
      const ease = 1 - Math.pow(1 - progress, 3); // ease-out cubic
      const position = start * (1 - ease);
  
      document.documentElement.scrollTop = position;
      document.body.scrollTop = position;
  
      if (progress < 1) {
        requestAnimationFrame(scrollStep);
      }
    }
  
    requestAnimationFrame(scrollStep);
  }
  </script>
  