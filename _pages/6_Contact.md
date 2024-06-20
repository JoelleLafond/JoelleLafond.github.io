---
layout: posts
permalink: /contact/
author_profile: true
title: '<p class="title-post" > Contact </p>'
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/banner8.jpg
excerpt: '<p class="excerpt-post"> Email, social medias and research networking</p>' 
---

<h1>How to contact me</h1>

The quickest and most certain way to contact me remains emailing me at: 

<p align="center" style="color:blue"> joelle.lafond [at] umontreal.ca </p>
<p align="center"> or </p>
<p align="center" style="color:blue"> joelle.lafond [at] ubc.ca </p>

Note that I may be more responsive using the first email address, as the latter is not lookable on mobile apps. You can also reach out to me or follow my work with these social media and websites:

<div class="center_contact">

  <a href="https://twitter.com/JoelleLafond">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="80px" src="../assets/images/twitter.png" />
   </a>

   <a href="https://bsky.app/profile/joellelafond.bsky.social">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="80px" src="../assets/images/bsky.png" />
   </a>

   <a href="https://www.researchgate.net/profile/Joelle-Lafond-2">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="80px" src="../assets/images/researchgate.png"  />
   </a>

  <a href="https://orcid.org/0000-0002-9844-2960">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="80px" src="../assets/images/orcid.png" />
   </a>

   <a href="https://scholar.google.com/citations?user=24nu_VAAAAAJ&hl=fr">
    <img style="float: left; Padding: 10px 10px 10px 10px;" width="80px" src="../assets/images/scholar.png" />
   </a>

</div>

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