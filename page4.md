<html>

<h1> Landmarks </h1>  
<head>
<style>
.center {
  margin: auto;
  width: 50%;
  border: 3px solid #ff9933;
  padding: 15px;
}
</style>
</head>
<body>

<h2>Information: Landmarks across South America</h2>


<div class="center">
 <p> Hover your pointer over the images to identify the name and location of each landmark.</p>
    <p><iframe src="https://h5p.org/h5p/embed/1236164" width="911" height="710" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Image Slider. Hover your pointer over the Image to see the names of each landmark."></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script></p>
 </div>
 
<h3> Understanding: Based on the images above, complete this crossword. Include an underscore between each word (_) if the landmark's name is more than one word.</h3>

<iframe src="https://h5p.org/h5p/embed/1236165" width="500" height="100" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Crossword"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

/* The grid: One column */
.column {
  float: left;
  width: 100%;
  padding: 50px;
  text-align: center;
  font-size: 25px;
  cursor: pointer;
  color: white;
}

.containerTab {
  padding: 20px;
  color: white;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Closable button inside the container tab */
.closebtn {
  float: right;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>
</head>
<body>

<div style="text-align:center">
 <h2>Extra Activity: Landmark Location </h2>
  <p>Click on the box below to complete the task</p>
</div>

<!-- Three columns -->
<div class="row">
  <div class="column" onclick="openTab('b1');" style="background:#ff9933;">
    Landmark Location
  </div>

</div>

<!-- Full-width columns: (hidden by default) -->
<div id="b1" class="containerTab" style="display:none;background:#ffcc00">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <h2>Answer the questions below based on what you have learnt</h2>
  <p><iframe src="https://h5p.org/h5p/embed/1237856" width="688" height="1091" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Landmark Locations"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script></p>
</div>



<script>
function openTab(tabName) {
  var i, x;
  x = document.getElementsByClassName("containerTab");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  document.getElementById(tabName).style.display = "block";
}
</script>
</body>
</html>




