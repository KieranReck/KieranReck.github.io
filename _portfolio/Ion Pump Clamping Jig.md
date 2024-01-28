---
title: "Ion Pump Clamping Jig"
excerpt: "Breathing Circuits for Active Humidification are plagued by one major issue, condensation. As the patient’s warm humid air supply..."
layout: single
classes: wide
header:
    image: /assets/images/IonPumpClampingJig_highlight.jpg
    teaser: /assets/images/IonPumpClampingJig_highlight.jpg
---

Electron Microscopes need to be sealed tight against the outside environment, and I mean really tight. When looking at things in nano-scale, dirt, particulates, and even air molecules will ruin your image. To avoid this issue, SEMs (Scanning Electron Microscopes) work under a state of "Ultra High Vacuum", a vacuum so empty that you could theoretically travel 40km before bumping into your first air molecule! The negative pressure this creates is huge (-1450psi / -100bar) and all of that pressure is trying to suck the outside air into the SEM. Standard seals won't cut it, so instead, you use something called a ConFlat. 

A ConFlat seal is a thin piece of metal that you deform between your two components by literally crushing it. This ensures that the seal plugs up any gaps but requires a fairly high crushing/clamping force to do so. Usually, this is fine, other than the spanner making your hands a little sore, but there is one component in the SEM that feels like it is designed to ruin your day, the Ion Pump.

![Ion-Pump-Nut-Problem](/assets/images/Ion-Pump-Nut-Problem.jpg){: .align-center width="800px"}

On this specific Ion Pump, when you try to use your spanner the connector gets in the way. You have to use a thinner spanner, but that means you are compromising on the strength of the tool. This is causing them to break regularly, and with the Ion Pump assembly weighing 40kg you have a recipe for things getting dropped and technicians getting hurt. 

To intervene, I undertook a Sustain project to create a Clamp to hold the Ion Pumps during this process. If people are breaking spanners there must be a lot of force going through the system, so this Clamp needs to be strong with very little flex. Space is limited in the cleanroom and the option to pack away the Clamp when not in use is important, so a semi-permanent fixture to the workbench will be required.

## Design Specification

- Strong enough to withstand the forces

- Leave the desk unobstructed when not in use

- Semi-permanent fixtures

- Quick to set up and use

## Final Product

<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        * {
        box-sizing: border-box;
        }
        /* Create your layouts. Here, I start by defining an uneven 2column style (-photos)
        /* followed by defining an even 2column style (-dual-even) which is used across multiple secions*/
        /* ....*/
        /* Create two unequal columns that floats next to each other */
    .column-photos {
        float: left;
        padding: 10px;
        height: max-content; /* Should be removed. Only for demonstration */
    }
    .left-photos {
        width: 35%;
    }
    .right-photos {
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
        .column-photos {
        width: 100%;
        height: max-content;
        }
    }
    </style>
</head>
<body>
    <div class="row">
        <div class="column-photos left-photos">
            <p><img src="/assets/images/IonPumpClampingJig_highlight.png"></p>           
        </div>
        <div class="column-photos right-photos">
            <p><img src="/assets/images/Ion-Pump-Jig-Disassembled.png"></p>
        </div>
    </div>
    <div class="row">
    </div>
    <br>
</body>
</html>

There is a fine line between strong and excessive and this welded 3mm sheet steel assembly walks it wonderfully. It is sturdy, but when put to the test it has an ever so slight flex indicating that it is just the right thickness to withstand a lifetime of use. Whilst the Clamp overall doesn't make it easier to tighten the ConFlat seal, it does make the whole process less fiddly and less dangerous for the engineer. The Ion Pumps fit snugly and are easy to locate, which is important when they weigh so much, and the toggle clamps offer a quick securing mechanism.

There are permanent brackets fixed to the framework underneath each workbench, offering a secure method of affixing the Clamps whilst leaving the tabletop clear when not in use. Each bracket has a rounded hem to protect the engineers from injury, a feature that they were very happy with. The Clamp is secured to the Brackets using machine screws.

The resounding feedback from the engineers who use it was "please can we have more of them", so I would say it is a success.

## Lessons Learned

- The limits of how close holes can be to a sheet metal bend (learn more in this blog post)

- Designing and working with welded sheet metal assemblies.

- https://geomiq.com/ offer an extensive and free sheet metal design guide.

- Sometimes the goalposts move (learn more in this blog post), ensure that you involve the technicians who will work directly with the jig, even if they aren't the main authority.

