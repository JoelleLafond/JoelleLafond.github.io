---
layout: posts
permalink: /Experience/
author_profile: true
title: '<p class="title-post" > Academic Experiences </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner11.jpg
excerpt: '<p class="excerpt-post"> Curriculum vitae </p>' 
---


<h2> Check out my CV for an up-to-date list of my academic experiences! </h2>

<div style="text-align: justify"><span style="color:#3778C6;" align="justify"> Last Updated: May 2nd, 2025 </span> </div>

<embed src="../assets/files/JLafond_CV.pdf" width="800px" height="800px" />


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
  