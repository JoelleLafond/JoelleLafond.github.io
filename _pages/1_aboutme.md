---
layout: posts
permalink: /About/
author_profile: true
title: '<p class="title-post" > About Me </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner4.jpg
excerpt: '<p class="excerpt-post"> Background, hobbies and values</p>' 
---

<h1> A little background </h1>

<p align="justify">
I have always been captivated by the unexpected and intriguing phenomena that arise in the study of biology. It was then only natural for me to gravitate towards atypical reproductive processes, which led me to pursue a PhD project focused on understanding the reproduction of the diploid and triploid hybrid fish <i>Chrosomus eos-neogaeus</i>. 
</p>

<img-div>
<img width="600px" src="../assets/images/About5.jpg" class="center" />
<figcaption>Some field work during my PhD</figcaption>
</img-div>


<p align="justify">
As a first-generation scholar and woman from a modest background, I've navigated significant challenges in pursuing my academic and professional goals in science. These experiences, however, have forged a deep well of resilience, determination, and a passionate commitment to scientific advancement.

Throughout my journey, I've learned the value of perseverance, hard work, and the power of collaborative learning. I'm incredibly proud of my accomplishments and deeply grateful to the mentors, colleagues, and loved ones who have supported me.

My experiences have fueled my desire to cultivate a more diverse, equitable, and inclusive scientific community, where individuals from all backgrounds can thrive and contribute their unique perspectives.

This vision, I believe, starts with customized teaching and mentoring approaches that acknowledge each mentee's past experiences and future aspirations. By tailoring our guidance, we can empower them to excel and reach their full potential.
</p>


<p align="justify">
As for my hobbies, I am found of nature, and will always be surprise by how diverse it can be. My hobbies includes wildlife photography, arts (mostly with natural subjects) and taking care of my three lovely cats! 
</p>

<img-div>
<img style="Padding: 10px 10px 10px 10px; float:left;" width="525px" src="../assets/images/About1.jpg"/>
<img style="Padding: 10px 10px 10px 10px;" width="525px" src="../assets/images/About2.jpg"/>
<img style="Padding: 10px 10px 10px 10px;float:left;" width="525px" src="../assets/images/About3.jpg"/>
<img style="Padding: 10px 10px 10px 10px;" width="525px" src="../assets/images/About6.jpg"/>
<figcaption>Some places where we went for fish samplings during my PhD</figcaption>
</img-div>



<!-- Back to top button -->
<button type="button" class="btn btn-danger btn-floating btn-lg" id="btn-back-to-top">
  <i class="fas fa-arrow-up"></i>
</button>

<script>
//Get the button
let mybutton = document.getElementById("btn-back-to-top");

// When the user scrolls down 20px from the top of the document, show the button
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
// When the user clicks on the button, scroll to the top of the document
mybutton.addEventListener("click", backToTop);

function backToTop() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>