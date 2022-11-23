---
layout: post
title: "Creating a 8.5mm motor micro quadcopter"
date: 2017-12-30 20:45:00 
description: There are other models out there, that require fasteners, or components that aren't essentials, so I aimed to fix that!
img: Copter_Assembly_Final_Render.png
tags: [Drone,Robotics,Robots,Design,3D-Printing,]
---

I had recently taken a Coursera course on Aerial Robotics, so I was interested in getting something drone-related started. There are some awesome setups for micro quad copters out there, but they all need fasteners to keep multiple parts together, and multiple parts seemed aggravating. I figured, I could design and print a single body to hold all of the components, so I got to work.

I started out with these components:

[Micro Scisky 32bit Microcontroller](https://www.banggood.com/Micro-Scisky-32bits-Brushed-Flight-Control-Board-Built-in-FlySky-Compatible-RX-For-DIY-Micro-Frame-p-1093312.html?rmmds=myorder&cur_warehouse=CN)

[3.7V 500mAh Battery x2]()

[Battery Connectors](https://www.banggood.com/Wholesale-Walkera-Hubsan-X4-Eachine-H8-1-to-5-Balance-Charging-Cable-For-3_7V-Battery-p-68437.html?rmmds=myorder&cur_warehouse=CN)

[Brushed DC Motors (2 packs of 2)](https://www.banggood.com/2-X-8x20mm-Motor-For-Hubsan-X4-H107C-H107D-RC-Quadcopter-p-87683.html?rmmds=myorder&cur_warehouse=CN)

[Ladybird Propellors (1 pack of 4)](https://www.banggood.com/Wholesale-3-Set-Walkera-QR-Ladybird-Spare-Parts-Main-Blades-Propellers-QR-Ladybird-Z-01-p-47127.html?rmmds=myorder&cur_warehouse=CN)

[Battery Charger](https://www.banggood.com/X6-6-In-1-Charger-For-Hubsan-X4-WLtoys-UDI-JXD-JJRC-Syma-JXD-p-965757.html?rmmds=myorder&cur_warehouse=CN)

[FlySky FS-i6 2.4G RC Transmitter](https://www.banggood.com/FlySky-FS-i6-2_4G-6CH-AFHDS-RC-Transmitter-With-FS-iA6B-Receiver-p-983537.html?rmmds=myorder&cur_warehouse=CN)

I also purchased the following components (although they weren't used or designed for until iteration 3):

[Eachine EV800 5 Inches 800x480 FPV Goggles](https://www.banggood.com/Eachine-EV800-5-Inches-800x480-FPV-Goggles-5_8G-40CH-Raceband-Auto-Searching-Build-In-Battery-p-1053357.html?rmmds=myorder)

[600TVL 1/4 1.8mm CMOS FPV 170 Degree Wide Angle Lens Camera PAL/NTSC 3.7-5V](https://us.banggood.com/Wholesale-Warehouse-600TVL-8_0MP-14-2_8mm-CMOS-FPV-170-Degree-Wide-Anlge-Lens-Camera-PALNTSC-wp-Usa-984345.html?rmmds=myorder)

[Pololu 5V Step-Up Voltage Regulator U3V12F5](https://www.pololu.com/product/2115)

## Iteration 1

In the beginning I wanted to create a solid body that held the 32 bit Micro SciSky controller and all four of the 8.5mm Motors. Once I was comfortable with the base, I knew I would add in the other component slots (battery and camera). I created the base to have an open bottom and rubber band straps, so that no tape was needed. The components were selected based on the requirements of the various components.

![Iteration 1]({{site.baseurl}}/assets/img/Copter_Body_V1.PNG)

## Iteration 2

This body, was more rigid. In the previous iteration, the arms of the drone bent inwards due to the force the propellors caused, and instead of creating a pull directly upwards they pulled towards the center of the copter body. To address this, I created a stabilizing circle on the outside of the core body.

![Iteration 2]({{site.baseurl}}/assets/img/Copter_Body_V2.PNG)

Fully assembled and ready to go!

![Iteration 2]({{site.baseurl}}/assets/img/IMG_4592.JPG)

## Iteration 3

Iteration 3 began to use the vertical space available in the center. This allowed me to put the control system on the base layer, and the batter on the top layer for easy access and replacement. Because of how small this drone is (and how inexpensive the battery is), battery life was ~5 minutes, so easy access was necessary.

![Iteration 3]({{site.baseurl}}/assets/img/Copter_ Body_V3.PNG)

Final assembly!

![Iteration 3]({{site.baseurl}}/assets/img/IMG_4593.JPG)

Iteration 3 was the model that I decided to finish with, it has a good balance of structure and weight - so I had to prepare it for printing. I manually added supports to the arches and overhangs so that the model would print well on my Monoprice select mini. The total print time is about 3 hours, so if anything was to happen to the model, I could just reprint and reassemble. Reassembly takes about 5 minutes and all of the components fit quite nicely together.

![Iteration 3 with supports]({{site.baseurl}}/assets/img/Copter_Body_V3.1.PNG)

Maiden Voyage!

![Iteration 3 with supports]({{site.baseurl}}/assets/vids/ezgif.com-gif-maker (4).gif)

