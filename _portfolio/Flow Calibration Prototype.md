---
title: "Flow Calibration Prototype"
excerpt: "Concept gas flow meter to be sold as an accessory for calibrating critical care medical devices in the field."
layout: single
tagline: "Professional Portfolio Project"
header:
    overlay_image: /assets/images/flow-calibration-header.jpg
    overlay_filter: "0.4"
    teaser: /assets/images/flow-calibration-header.jpg
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
        width: 50%;
    }
    .right-intro {
        width: 50%;
    }
    /* Clear floats after the columns */
    .row:after {
        content: "";
        display: table;
        clear: both;
    }
    .column-triple {
        float: left;
        padding: 10px;
        height: max-content; /* Should be removed. Only for demonstration */
    }
    .left-triple, .right-triple, .middle-triple {
        width: 33%;
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
        @media screen and (max-width: 800px) {
        .column-triple {
        width: 100%;
        height: max-content;
        }
    }
    </style>
</head>
<body>
<h2>Project Brief</h2>
<p>Lead the production of a concept gas flow meter to be sold as an accessory for calibrating critical care medical devices in the field. Combine an off-the-shelf mass flow sensor with an LED display and a pressure sensor to provide full functionality whist outperforming competitor devices whilst retailing at a vastly cheaper price point. </p>
    <div class="row">
        <div class="column-intro left-intro">
            <h2>Proof of Concept</h2>
            <p>The first step was to produce a functional prototype utilising the intended hardware and sensors. During this phase the initial code was produced, hardware choices were finalised and tests were run comparing the industry standard device to this proof of concept to ensure the accuracy of the flow, pressure, temperature, and humidity measurements were at the standard required.</p>              
        </div>
        <div class="column-intro right-intro">
            <p><img src="/assets/images/flow-calibration-initial-prototype.jpg" align="right"></p>
        </div>
    </div>
    <div class="row">
        <div class="column-triple left-triple">
            <p><img src="/assets/images/flow-calibration-concept-sketch1.jpg" align="left" style="max-width:100%"></p>            
        </div>
        <div class="column-triple middle-triple">
            <p><img src="/assets/images/flow-calibration-concept-sketch2.jpg" align="center" style="max-width:100%"></p>
        </div>
        <div class="column-triple right-triple">
            <p><img src="/assets/images/flow-calibration-concept-sketch3.jpg" align="right" style="max-width:100%"></p>
        </div>
    </div>
    <div class="row">
        <div class="column-intro left-intro">
            <p><img src="/assets/images/flow-calibration-early-3dprints.jpg" align="left"></p>              
        </div>
        <div class="column-intro right-intro">
            <h2>Rapid Prototyping</h2>
            <p>With the components finalised I began designing and modelling concepts for the housing, each considering the assembly process, aesthetics, usability, and issues specific to injection moulding such as where split lines would be situated. To keep production costs low each housing was designed to be produced using only simple two-part mould tools, without any cores or side actions.</p>
            <p>3D printing proved invaluable in this process, allowing quick production of concepts which could be handled, examined and critiqued in the iterative process of design.</p>
        </div>
    </div>
    <div class="row">
        <div class="column-intro left-intro">
            <h2>Keeping Costs Low</h2>
            <p>With price being a key element of this product every effort was made to keep potential manufacturing costs low. The housings incorporated a medical connector and a button both taken from other products in the company’s roster to benefit from economies of scale. Should the product go to manufacture these components could be produced in the devices colour scheme using the same pre-existing mould tooling.</p>              
        </div>
        <div class="column-intro right-intro">
            <p><img src="/assets/images/flow-calibration-early-3dprints2.jpg" align="right"></p>
        </div>
    </div>
    <div class="row">
        <div class="column-intro left-intro">
            <p><img src="/assets/images/flow-calibration-custom-electronics.jpg" align="left"></p>              
        </div>
        <div class="column-intro right-intro">
            <h2>Custom Electronics</h2>
            <p>Working with the electrical engineering team the components were condensed onto a custom PCB and work began on the code and user interface. The device used a single button to cycle between Flow Rate, Temperature, Humidity, Pressure, and a summary screen displaying all four measurements, as well as the ability to begin data logging to a microSD card.</p>
        </div>
    </div>
    <h2>The Final Prototype</h2>
    <div class="row">
        <p><img src="/assets/images/flow-calibration-final1.jpg" align="center"></p>
    </div>
    <div class="row">
        <p><img src="/assets/images/flow-calibration-final2.jpg" align="center"></p>
    </div>
</body>
</html>

