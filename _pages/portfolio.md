---
title: Portfolio
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
classes: wide
---


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
  height: max-content; /* Should be removed. Only for demonstration */
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
<div class="row">
  <div class="column left">
    <p><img src="/assets/images/Bio(4x5vertical).png" style="max-width:300px;width:100%"></p>
    <p></p>
  </div>
  <div class="column middle">
    <h2>Hi, I'm Kieran</h2>
    <p></p>
    <p>A Mechanical Engineer with a passion for problem-solving. Whether it’s continuous improvement, optimising designs for manufacture, or developing electromechanical devices, my career has led me to an array of work with products from concept through to manufacture and beyond, revealing a love for mechatronics development. I am always interested to hear about exciting opportunities, so reach out.</p>
  </div>
</div>
</body>
</html>

***

<h1>Expertise</h1>

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
}
.left {
  width: 50%;
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
/* Responsive layout - makes the columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    height: max-content;
  }
}
</style>
</head>
<body>
<div class="row">
  <div class="column left">
    <p>Electromechanical Design and Development</p>
    <p>ISO 13485 Quality Management Systems</p>
    <p>Medical Device Directive (MDD)</p>
    <p>Design for Injection Moulding</p>
    <p>Continuous Improvement</p>
    <p>Consumer Devices</p>
    <p>Rapid Prototyping</p>
  </div>
  <div class="column middle">
    <p>IEC60601 for Medical Electrical Equipment</p>
    <p>CSWP Certified Solidworks Professional</p>
    <p>Corrosive Marine Environments</p>
    <p>Sheet Metal Assemblies</p>
    <p>Design for Assembly</p>
    <p>Mechanical Design</p>
    <p>3D Printing</p>
  </div>
</div>
</body>

***

<h1>Career</h1>

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
}
.left {
  width: 50%;
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
/* Responsive layout - makes the columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    height: max-content;
  }
}
</style>
</head>
<body>
<div class="row">
  <div class="column left">
    <h3>Medical Device Development</h3>
    <p>2018 - 2019</p>
    <p>&nbsp</p>
    <h3>Marine Optical Instruments</h3>
    <p>2019 - 2020</p>
  </div>
  <div class="column middle">
    <h3>Electron Microscopy</h3>
    <p>2020 - 2023</p>
    <p>&nbsp</p>
    <h3>Infectious Disease Diagnostics</h3>
    <p>2023 - Present</p>
  </div>
</div>
</body>

***


Electromechanical Design and Development

ISO 13485 Quality Management Systems

Medical Device Directive (MDD)

Design for Injection Moulding

Continuous Improvement

Consumer Devices

Rapid Prototyping

<html>

 <head>

    <style>

    {

        box-sizing: border-box;

    }

    /* Set additional styling options for the columns*/

    .column {

    float: left;

    width: 50%;

    }

  

    .row:after {

    content: "";

    display: table;

    clear: both;

    }

    </style>

 </head>

 <body>

    <div class="row">

        <div class="column" style="background-color:#FFB695;">

            <h2>Column 1</h2>

            <p>Data..</p>

        </div>

        <div class="column" style="background-color:#96D1CD;">

            <h2>Column 2</h2>

            <p>Data..</p>

        </div>

    </div>

 </body>

</html>

<html>
 <head>
    <style>
    .column {
    float: left;
    width: 50%;
    }

    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    </style>
 </head>
 <body>
    <div class="row">
        <div class="column">
            <h2>Column 1</h2>
            <p>Data..</p>
        </div>
        <div class="column">
            <h2>Column 2</h2>
            <p>Data..</p>
        </div>
    </div>
 </body>
</html>


# You can make a table with invisible border using
border: 0px
```
<html>
<head>
<style>
table, th, td {
  border: 1px solid red;
  border-collapse: collapse;
  width: 100%;
  text-align: center;
}
</style>
</head>
<body>

<h2>Table With Invisible Borders</h2>

<p>Style the table with white borders and a background color of the cells to make the impression of invisible borders.</p>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th style="width:60%">Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>
```


<html>
<style>
table, th, td {
  border: 1px solid red;
  border-collapse: collapse;
  text-align: center;
}
</style>
<body>

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th style="width:70%">Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>80</td>
  </tr>
</table>

</body>
</html>

# Having 2 tables like this in a single page would mean that they have to share style settings


# You can make a table with invisible border using
border: 0px

# Table format is already defined by the theme, i wonder if this is classing. I should look into making a custom css class for transparent tables and various alignment table types

# Try pasting the existing table css class into an online generator to see if it matches the website



IEC60601 for Medical Electrical Equipment

CSWP Certified Solidworks Professional

Corrosive Marine Environments

Sheet Metal Assemblies

Design for Assembly

Mechanical Design

3D Printing
***
# Competencies

--insert gallary here--
https://mmistakes.github.io/minimal-mistakes/post%20formats/post-gallery/

# Career

