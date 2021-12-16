---
title: Page2
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h2>Two Equal Columns</h2>

<div class="row">
  <div class="column" style="background-color:#aaa;">
      <h2>Indigenous Languages</h2>
  <p>Watch the first four minutes of video to learn more about the languages in South America!
  <iframe width="280" height="158" src="https://www.youtube.com/embed/US-sSO0Pc3Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>How much did you understand?</h2>
  <p>Answer the questions to test you understanding.
<iframe src="https://h5p.org/h5p/embed/1235829" width="911" height="294" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Example Content - Single Choice Set"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>
  </p>
  </div>
</div>

</body>
</html>
