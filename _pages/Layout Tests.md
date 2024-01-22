---
title: Layout Tests
layout: single
permalink: /layout_tests/
---

You have stumbled across my test page for working out how the hell to add HTML layouts to this mostly Markdown based website.
Whilst my blog is almost entierly markdown, my Professional page needed a little more customisation to make it pop. I have achieved this partially thanks to the layout tests below:


# Here's a layout test using a HTML column layout. 

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

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive Two Column Layout</h2>
<p>Resize the browser window to see the responsive effect (the columns will stack on top of each other instead of floating next to each other, when the screen is less than 600px wide).</p>

<div class="row">
  <div class="column" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>


***

# Now lets turn it invisible 
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

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive Two Column Layout</h2>
<p>Resize the browser window to see the responsive effect (the columns will stack on top of each other instead of floating next to each other, when the screen is less than 600px wide).</p>

<div class="row">
  <div class="column">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>


***


# Can we turn the heading divider off?
The previous table shows are grey divider between the column heading and the column text, lets try removing it
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
  border: 0px solid red;
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

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive Two Column Layout</h2>
<p>Resize the browser window to see the responsive effect (the columns will stack on top of each other instead of floating next to each other, when the screen is less than 600px wide).</p>

<div class="row">
  <div class="column">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>



***




# what if we simply remove the column headings?
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

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive Two Column Layout</h2>
<p>Resize the browser window to see the responsive effect (the columns will stack on top of each other instead of floating next to each other, when the screen is less than 600px wide).</p>

<div class="row">
  <div class="column">
    <p>Some text..</p>
  </div>
  <div class="column">
    <p>Some text..</p>
  </div>
</div>

</body>
</html>



***



# or if we remove the column paragraths?
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

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive Two Column Layout</h2>
<p>Resize the browser window to see the responsive effect (the columns will stack on top of each other instead of floating next to each other, when the screen is less than 600px wide).</p>

<div class="row">
  <div class="column">
    <h2>Column 1</h2>
  </div>
  <div class="column">
    <h2>Column 2</h2>
  </div>
</div>

</body>
</html>


***



# Can we have multiple paragrath rows?
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

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive Two Column Layout</h2>
<p>Resize the browser window to see the responsive effect (the columns will stack on top of each other instead of floating next to each other, when the screen is less than 600px wide).</p>

<div class="row">
  <div class="column">
    <p>Some text..</p>
    <p>Some more text..</p>
  </div>
  <div class="column">
    <p>Some text..</p>
    <p>Some more text..</p>
  </div>
</div>

</body>
</html>


***




# Can we do some text alignment?
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

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive Two Column Layout</h2>
<p>Resize the browser window to see the responsive effect (the columns will stack on top of each other instead of floating next to each other, when the screen is less than 600px wide).</p>

<div class="row">
  <div class="column">
    <p style="text-align:center;">Some text..aligned center</p>
    <p>Some more text..</p>
  </div>
  <div class="column">
    <p>Some text..</p>
    <p>Some more text..</p>
  </div>
</div>

</body>
</html>



***


# What about some uneven width columns?
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

.left {
  width: 25%;
}

.middle {
  width: 75%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

</style>
</head>
<body>

<h2>Two Unequal Columns</h2>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <h2>Left Column</h2>
    <p>Some text..</p>
  </div>
  <div class="column middle" style="background-color:#ccc;">
    <h2>Middle Column</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>


# ...how about three columns?
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create three unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

.left, .right {
  width: 25%;
}

.middle {
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

</style>
</head>
<body>

<h2>Three Unequal Columns</h2>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <h2>Column 1</h2>
    <p>Some text..</p>
  </div>
  <div class="column middle" style="background-color:#bbb;">
    <h2>Column 2</h2>
    <p>Some text..</p>
  </div>
  <div class="column right" style="background-color:#ccc;">
    <h2>Column 3</h2>
    <p>Some text..</p>
  </div>
</div>

</body>
</html>


***



# Put it all together:
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create three unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}

.left, .right {
  width: 25%;
}

.middle {
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

</style>
</head>
<body>

<h2>Three Unequal Columns</h2>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <p>Column1</p>
    <p>Some more text..</p>
  </div>
  <div class="column middle" style="background-color:#aab;">
    <p>Column half width</p>
    <p>Some more text..</p>
  </div>
  <div class="column right" style="background-color:#aac;">
    <p style="text-align:center;">Some text..aligned center</p>
    <p style="text-align:right;">Some text..aligned right</p>
  </div>
</div>

</body>
</html>


***


# Lets try aligning some images

# Put it all together:
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create three unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}

.left, .right {
  width: 25%;
}

.middle {
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

</style>
</head>
<body>

<h2>Three Unequal Columns</h2>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <p>relative Markdown Links dont work</p>
    <p>![test](../assets/images/test.png)</p>
  </div>
  <div class="column middle" style="background-color:#aab;">
    <p>use HTML "img src=""" links instead</p>
    <p><img src="/assets/images/test.png"></p>
  </div>
  <div class="column right" style="background-color:#aac;">
    <p style="text-align:center;">nothing here</p>
    <p style="text-align:right;">nothing here either</p>
  </div>
</div>

</body>
</html>


# Lets try BIGGER images

# Put it all together:
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create three unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}

.left, .right {
  width: 25%;
}

.middle {
  width: 50%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}

</style>
</head>
<body>

<h2>Three Unequal Columns</h2>

<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <p>relative Markdown Links dont work</p>
    <p>![test](../assets/images/test.png)</p>
  </div>
  <div class="column middle" style="background-color:#aab;">
    <p>1200px wide HTML Image willreactively adjust to the width of the column</p>
    <p><img src="/assets/images/test.png" width="1200"></p>
  </div>
  <div class="column right" style="background-color:#aac;">
    <p style="text-align:center;">nothing here</p>
    <p style="text-align:right;">nothing here either</p>
  </div>
</div>

</body>
</html>


# What if you have large cell contents which will overlap eachother when the columns react?

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: 375px; /* Should be removed. Only for demonstration */
}
.left {
  width: 30%;
}
.middle {
  width: 70%;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>
<h2> When you make the window smaller, the image ends up behind the text</h2>
<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <p><img src="/assets/images/Bio(4x5vertical).png"></p>
    <p></p>
  </div>
  <div class="column middle" style="background-color:#bbb;">
    <h2>Hi, I'm Kieran</h2>
    <p></p>
    <p>A Mechanical Engineer with a passion for problem-solving. Whether it’s continuous improvement, optimising designs for manufacture, or developing electromechanical devices, my career has led me to an array of work with products from concept through to manufacture and beyond, revealing a love for mechatronics development. I am always interested to hear about exciting opportunities, so reach out.</p>
  </div>
</div>
</body>
</html>

***

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: min-content; /* Should be removed. Only for demonstration */
}
.left {
  width: 30%;
}
.middle {
  width: 70%;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    height: max-content;
  }
}
</style>
</head>
<body>
<h2> The solution is to add "height: min-content;" to your react code </h2>
<div class="row">
  <div class="column left" style="background-color:#aaa;">
    <p><img src="/assets/images/Bio(4x5vertical).png"></p>
    <p></p>
  </div>
  <div class="column middle" style="background-color:#bbb;">
    <h2>Hi, I'm Kieran</h2>
    <p></p>
    <p>A Mechanical Engineer with a passion for problem-solving. Whether it’s continuous improvement, optimising designs for manufacture, or developing electromechanical devices, my career has led me to an array of work with products from concept through to manufacture and beyond, revealing a love for mechatronics development. I am always interested to hear about exciting opportunities, so reach out.</p>
  </div>
</div>
</body>
</html>