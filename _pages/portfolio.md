---
title: Portfolio
browser_title: Portfolio \| Kieran Reck
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
classes: 
gallery1:
  - url: /assets/images/solidworks-vector-logo-400x172.png
    image_path: /assets/images/solidworks-vector-logo-400x172.png
  - url: /assets/images/SAP Logo.png
    image_path: /assets/images/SAP Logo.png
  - url: /assets/images/Seimans NX.png
    image_path: /assets/images/Seimans NX.png
gallery2:
  - url: /assets/images/PTC_Creo Transparent.png
    image_path: /assets/images/PTC_Creo Transparent.png
  - url: /assets/images/ANSYS_logo.png
    image_path: /assets/images/ANSYS_logo.png
gallery3:
  - url: /assets/images/Fusion-360-Logo rectangular transparent.png
    image_path: /assets/images/Fusion-360-Logo rectangular transparent.png
  - url: /assets/images/star-logo transparent.png
    image_path: /assets/images/star-logo transparent.png
  - url: /assets/images/Siemens-solidedge_450x200 Transparent.png
    image_path: /assets/images/Siemens-solidedge_450x200 Transparent.png
---
---


<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
/* Create your layouts. Here, I start by defining an uneven 2column style (-intro)
/* followed by defining an even 2column style (-dual-even) which is used across multiple secions*/
/* ....*/
/* Create two unequal columns that floats next to each other */
  .column-intro {
    float: left;
    padding: 10px;
    height: max-content; /* Should be removed. Only for demonstration */
  }
  .left-intro {
    width: 35%;
  }
  .right-intro {
    width: 65%;
  }
  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  /* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
  @media screen and (max-width: 600px) {
    .column-intro {
      width: 100%;
      height: max-content;
    }
  }
  /* now create a two column layout for the copmpetancies*/
    .column-Competencies {
    float: left;
    padding: 10px;
    height: max-content; /* Should be removed. Only for demonstration */
  }
  .left-Competencies {
    width: 24%;
  }
  .right-Competencies {
    width: 76%;
  }
  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  /* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
  @media screen and (max-width: 600px) {
    .column-Competencies {
      width: 100%;
      height: max-content;
    }
  }
/* Now Create a three column layout */
  .column-triple {
    float: left;
    padding: 10px;
  }
  .left-triple {
    width: 24%;
  }
  .right-triple, .middle-triple {
    width: 38%;
  }
  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  /* Responsive layout - makes the columns stack on top of each other instead of next to each other */
  @media screen and (max-width: 600px) {
    .column-triple {
      width: 100%;
      height: max-content;
    }
  }
/* Create highlight projects layout */
  .column-highlight {
    float: left;
    padding: 10px;
    height: max-content; /* Should be removed. Only for demonstration */
  }
  .left-highlight {
    width: 50%;
  }
  .right-highlight {
    width: 50%;
  }
  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  /* Chose to remove the responsive layout because otherwise it stacks weirdly due to the pictures alternating sides 
    Responsive layout - makes the three columns stack on top of each other instead of next to each other 
  @media screen and (max-width: 600px) {
    .column-highlight {
      width: 100%;
      height: max-content;
    }
  } */
/* add some HTML button classes */
  /*@import "https://github.com/KieranReck/KieranReck.github.io/blob/f465a8e0b015112d3d9264e8ec32edd6d4859ef8/_sass/minimal-mistakes/_buttons.scss";*/ 

</style>
</head>

<body>
<div class="row">
  <div class="column-intro left-intro">
    <p><img src="/assets/images/Bio(4x5vertical).png" style="max-width:350px;width:100%"></p>
    <p></p>
  </div>
  <div class="column-intro right-intro">
    <h1></h1>
    <h1>Hi, I'm Kieran</h1>
    <p></p>
    <p>A Mechanical Engineer with a passion for problem-solving. Whether it’s continuous improvement, optimising designs for manufacture, or developing electromechanical devices, my career has led me to an array of work with products from concept through to manufacture and beyond, revealing a love for mechatronics development. I am always interested to hear about exciting opportunities, so reach out.</p>
  </div>
</div>
</body>
</html>

<body>
<div class="row">
  <div class="column-triple left-triple">
    <h1>Expertise</h1>
  </div>
  <div class="column-triple middle-triple">
    <p>Electromechanical Design and Development</p>
    <p>ISO 13485 Quality Management Systems</p>
    <p>Medical Device Directive (MDD)</p>
    <p>Design for Injection Moulding</p>
    <p>Continuous Improvement</p>
    <p>Consumer Devices</p>
    <p>Rapid Prototyping</p>
  </div>
  <div class="column-triple right-triple">
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

<body>
<div class="row">
  <div class="column-Competencies left-Competencies">
    <h1>Competencies</h1>
  </div>
  <div class="column-Competencies right-Competencies">
    <p>{% include gallery id="gallery1" %}</p>
    <p>{% include gallery id="gallery2" %}</p>
    <p>{% include gallery id="gallery3" %}</p>
  </div>
</div>
</body>

***

<body>
  <div class="column-triple left-triple">
    <h1>Career</h1>
  </div>
  <div class="column-triple middle-triple">
  	<div class="row">
   	  <h3>Medical Device Development</h3>
   	  <p>2018 - 2019</p>
    </div>
  </div>
    <div class="column-triple right-triple">
      <div class="row">	
      <h3>Marine Optical Instruments</h3>
      <p>2019 - 2020</p>
    </div>
  </div>
  <div class="column-triple left-triple">
  </div>
  <div class="column-triple middle-triple">
    <div class="row">
      <h3>Scanning Electron Microscopy</h3>
      <p>2020 - 2023</p>
    </div>
  </div>	
    <div class="column-triple right-triple">
      <div class="row">
      <h3>Infectious Disease Diagnostics</h3>
      <p>2023 - Present</p>
    </div>
  </div>
<hr style="width:100%">
</body>
 

<h1>Highlight Projects</h1>
<body>
<div class="row">
  <div class="column-highlight left-highlight">
    <p><img src="/assets/images/SemipermeableTubes_highlight.jpg" style="max-width:500px;width:100%"></p>
    <p></p>
  </div>
  <div class="column-highlight right-highlight">
    <h2>Semipermeable Breathing Tubes</h2>
    <p></p>
    <p>Intensive Care breathing tubes for actively humidified circuits which get humidity to the patient without the risk of dangerous condensation buildup.</p>
    <a target="_blank" class="btn btn--primary btn--large" href="https://kieranreck.github.io/portfolio/Semipermeable%20Respiratory%20Tubes/">Learn More..</a>
  </div>
</div>
</body>


<body>
<div class="row">
  <div class="column-highlight left-highlight">
    <h2>Ion Pump Production Jig</h2>
    <p></p>
    <p>A sturdy clamp to hold Ion Pumps in place, withstanding the rotational forces induced during ConFlat Vacuum Seal installation.</p>
    <a target="_blank" class="btn btn--primary btn--large" href="https://kieranreck.github.io/portfolio/Ion%20Pump%20Clamping%20Jig/">Learn More..</a>
  </div>
  <div class="column-highlight right-highlight">
    <p><img src="/assets/images/IonPumpClampingJig_highlight.jpg" style="max-width:500px;width:100%"></p>
  </div>
</div>
</body>

<body>
<div class="row">
  <div class="column-highlight left-highlight">
    <p><img src="/assets/images/MedicalAirflowConcept_highlight.jpg" style="max-width:500px;width:100%"></p>
    <p></p>
  </div>
  <div class="column-highlight right-highlight">
    <h2>Medical Airflow Calibrator</h2>
    <p></p>
    <p>Accessory device that allows customers to calibrate their Medical Gas Blenders in the field, extending service periods and saving hospitals money in the long run.</p>
    <a target="_blank" class="btn btn--primary btn--large" href="https://kieranreck.github.io/portfolio/Flow%20Calibration%20Prototype/">Learn More..</a>
  </div>
</div>
</body>

# More Projects 
Click on a project to learn more... 

