---
title: "Power Down Alarm"
layout: posts
header:
    image: /assets/images/power-down-alarm-header.jpg
    teaser: /assets/images/power-down-alarm-header.jpg
---

A friend of mine always forgets to put the handbrake on, it’s amazing that her car is ever where she left it. So for Christmas, I gifted her this doohicky.


![power-down-alarm-main.jpg](/assets/images/power-down-alarm-main.jpg){: .align-center width="600px"}


![power-down-alarm-iso.jpg](/assets/images/power-down-alarm-iso.jpg){: .align-center width="600px"}

This little circuit sculpture sits in the car…waiting… suspiciously connected to a USB port. When the car is switched off and it loses power, the hold-up capacitors dump their charge into a Piezo Buzzer and “BEEEEEP”. Consider yourself ‘reminded’ to check the handbrake.

![power-down-alarm-beeep.jpg](/assets/images/power-down-alarm-beeep.jpg){: .align-center width="600px"}

In its simplest form, this circuit is a switch that either connects the capacitor to a power supply for charging, or to a buzzer for discharging. Swap that switch out for a relay whose coil is connected across the power supply and now it will automatically switch between the two when the power goes off. Add a second capacitor in parallel to make it beep for longer, add an LED to indicate when it is receiving power, and turn the whole thing into a circuit sculpture to make it look interesting. 

A great excuse to dip my toes into some circuitry and learn something new, and scare a friend along the way. 

## Schematic

![power-down-alarm-schematic.png](/assets/images/power-down-alarm-schematic.png){: .align-center width="600px"}

## Simplified Circuit
![power-down-alarm-circuit-simplified.jpg](/assets/images/power-down-alarm-circuit-simplified.jpg){: .align-center width="600px"}

## Full Circuit
![power-down-alarm-circuit-full.jpg](/assets/images/power-down-alarm-circuit-full.jpg){: .align-center width="600px"}

## Lessons Learned

- Hold-up capacitor circuit design

- Intro to Circuit Sculptures (can you tell I have been looking at [Mohit Bhoite’s](https://www.bhoite.com/sculptures/) work recently?)

- How to draw basic schematics on Fusion360 and that it isn't the best tool for the job. Use KiCAD instead!