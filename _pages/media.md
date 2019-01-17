---
layout: default
title: Media
permalink: /media/
avatar: true
navigation: true
---
<p style="float: left; font-size: 9pt; text-align: center; width: 15%; margin-right: 2%; margin-bottom: 2%;"><img src="https://i.imgur.com/Us2A1wl.jpg" style="width: 100%">Battery settings</p>
<p style="float: left; font-size: 9pt; text-align: center; width: 15%; margin-right: 2%; margin-bottom: 2%;"><img src="https://i.imgur.com/Us2A1wl.jpg" style="width: 100%">Battery settings</p>
<p style="float: left; font-size: 9pt; text-align: center; width: 15%; margin-right: 2%; margin-bottom: 2%;"><img src="https://i.imgur.com/Us2A1wl.jpg" style="width: 100%">Battery settings</p>
<p style="float: left; font-size: 9pt; text-align: center; width: 15%; margin-right: 2%; margin-bottom: 2%;"><img src="https://i.imgur.com/Us2A1wl.jpg" style="width: 100%">Battery settings</p>
<p style="float: left; font-size: 9pt; text-align: center; width: 15%; margin-right: 2%; margin-bottom: 2%;"><img src="https://i.imgur.com/Us2A1wl.jpg" style="width: 100%">Battery settings</p>
<p style="float: left; font-size: 9pt; text-align: center; width: 15%; margin-right: 2%; margin-bottom: 2%;"><img src="https://i.imgur.com/Us2A1wl.jpg" style="width: 100%">Battery settings</p><p style="clear: both;">
  
<!-- Trigger the Modal -->
<img id="myImg" src="https://i.imgur.com/Us2A1wl.jpg" style="width:100%;max-width:300px">

<!-- The Modal -->
<div id="myModal" class="modal">

  <!-- The Close Button -->
  <span class="close">&times;</span>

  <!-- Modal Content (The Image) -->
  <img class="modal-content" id="img01">

  <!-- Modal Caption (Image Text) -->
  <div id="caption"></div>
</div>

// Get the modal
var modal = document.getElementById('myModal');

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById('myImg');
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}
<button onclick="window.location.href = 'https://i.imgur.com/Us2A1wl.jpg';">Download</button>


