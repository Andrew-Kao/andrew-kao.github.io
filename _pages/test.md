---
permalink: /test.html
title: "Test"
excerpt: "Test component of website"
author_profile: true
sitemap: false
---
<!-- 
<head>
<style>
.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}
</style>  
</head> -->

<!-- class="btn--info" -->
<!-- <button  onclick="myFunction()">Abstract</button> -->
<a href="#!" class="btn--success" onclick="myFunction()">Abstract</a>
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
