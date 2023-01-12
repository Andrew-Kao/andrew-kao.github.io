---
permalink: /test.html
title: "Test"
excerpt: "Test component of website"
author_profile: true
sitemap: false
---



<button class="btn--info" onclick="myFunction()">Abstract</button>
<div id="myDIV" class="notice--info" style="display:none">
  Abstract text
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
