---
title: Page2
---
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
/* Style the buttons */
.btn {
  border: none;
  outline: none;
  padding: 12px 16px;
  background-color: #ff9933;
  cursor: pointer;
}

.btn:hover {
  background-color: #ff9933;
}

.btn.active {
  background-color: #ff9933;
  color: white;
}
</style>
</head>
<body>

<h2>Languages of South America</h2>


<div id="btnContainer">
  <button class="btn" onclick="listView()"><i class="fa fa-bars"></i> List</button> 
  <button class="btn active" onclick="gridView()"><i class="fa fa-th-large"></i> Grid</button>
</div>
<br>

<div class="row">
  <div class="column" style="background-color:#ff9933;">
    <p><div class="row">
  <div class="column" style="background-color:#ff9933;">
    <head>
<style>
.center {
  margin: auto;
  width: 80%;
  border: 5px solid #ffffff;
  padding: 10px;
}
</style>
</head>
<body>


<div class="center">
  <h2> Indigenous Languages</h2> 
<iframe width="1000" height="400" src="https://www.youtube.com/embed/US-sSO0Pc3Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</div>

</body>
</div>
  </div></p>
  </div>
  <div class="column" style="background-color:#ff9933;">
    <p><h2>Listen to the first four minutes of the video again then complete this quiz to see what you can remember.</h2>
  <p><iframe src="https://h5p.org/h5p/embed/1235829" width="400" height="400" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Example Content - Single Choice Set"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script></p></p>
  </div>
</div>

<div class="row">
  <div class="column" style="background-color:#ff9933;">
    <p><h2>Complete the word search!</h2>
  <p>  <div class="column" style="background-color:#ff9933;">
  <iframe src="https://h5p.org/h5p/embed/1235838" width="1090" height="789" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Find the countries in the word search below"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>
  </div></p>.</p>
  </div>
 

<script>
// Get the elements with class="column"
var elements = document.getElementsByClassName("column");

// Declare a loop variable
var i;

// List View
function listView() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.width = "100%";
  }
}

// Grid View
function gridView() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.width = "50%";
  }
}

/* Optional: Add active class to the current button (highlight it) */
var container = document.getElementById("btnContainer");
var btns = container.getElementsByClassName("btn");
for (var i = 0; i < btns.length; i++) {
  btns[i].addEventListener("click", function() {
    var current = document.getElementsByClassName("active");
    current[0].className = current[0].className.replace(" active", "");
    this.className += " active";
  });
}
</script>

</body>
</html>


