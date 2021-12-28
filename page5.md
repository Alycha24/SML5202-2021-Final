<html>


<h1> Climate </h1>  
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

<h2>Information: Climate in South America</h2>


<div class="center">
 <p> Click on each hotspot to read aboit the weather in each country. </p>
    <p><iframe src="https://h5p.org/h5p/embed/1237910" width="650" height="315" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Image Hotspots"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script></p>
 </div>
 
<h3> Understanding: Answer the questions below based on what you have read.</h3>

<iframe src="https://h5p.org/h5p/embed/1237913" width="696" height="225" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Example Content - Single Choice Set"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>
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
  <h2>Extra Activity: Weather Research</h2>
  <p>Click on the box below to see the activity</p>
</div>

<!-- Three columns -->
<div class="row">
  <div class="column" onclick="openTab('b1');" style="background:#ff9933;">
Weather Research
  </div>
 
</div>

<!-- Full-width columns: (hidden by default) -->
<div id="b1" class="containerTab" style="display:none;background:#ffcc00">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <h2>Click on the weather widget below to search the five South American Countries and compare the current weather in each country.</h2>
  <p><a class="weatherwidget-io" href="https://forecast7.com/en/40d71n74d01/new-york/" data-label_1="Paraguay" data-label_2="WEATHER" data-theme="original" >Paraguay WEATHER</a>
<script>
!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
</script></p>
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


