---
permalink: /test.html
title: "Test"
excerpt: "Test component of website"
author_profile: true
sitemap: false
---


<!-- <script type="text/html">
   <button onclick="myFunction()">Click Me</button>
  <div id="myDIV">
    This is my DIV element.
  </div> 
</script>
 -->

<button onclick="myFunction()">Click Me</button>
<div id="myDIV" style="display:none">
  This is my DIV element.
</div> 

<script type="text/javascript">
  function myFunction() {
  var x = document.getElementById("myDIV");
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
  x.style.display = "none";
  }
} 
</script>
