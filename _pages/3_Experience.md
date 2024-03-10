---
layout: posts
permalink: /Experience/
author_profile: true
title: '<p class="title-post" > Academic Experience </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner7.jpg
excerpt: '<p class="excerpt-post"> Curriculum vitae </p>' 
---


<h2> Check out my CV for an up-to-date list of my academic experience! </h2>
<div style="text-align: justify"><span style="color:#3778C6;" align="justify"> Last Updated: March 10th, 2024</span> </div>

<embed src="../assets/files/JLafond_CV.pdf" width="800px" height="800px" />


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