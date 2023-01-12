---
layout: post
title: "Designing a Gaming mouse in 24 hours or less."
date: 2023-01-11 20:45:00 
description: Ergonomic Gaming Mouse Design
img: LowProfileMouse16.jpg
tags: [Gaming,Design,3D-Printing,Engineering]
---

The goal of this project was to design a functional gaming mouse in 24 hours. 
Gaming mice differ from normal computer mice, in that they are usually used at a much higher frequency to normal gaming mice, they are rated for higher amounts of clicks, have higher or more customizable DPI (dots per inch) and often contain RGB (Red Green Blue) strips that are customizable.


## Start time: 6:30pm January 11th, 2023

## Proof of Concept
Time to make a really rough sketch to remember basic functions I'm going to be adding in.

![Sketch]({{site.baseurl}}/assets/img/LowProfileMouseSketch.jpg)

Having used the Sculpt function in Fusion 360 many times before, I knew that creating a mesh body and molding it into the form that I wanted was where I would start.
Knowing that this mouse had no electrical components selected, I was free to create a general mouse body without having to worry about fitting components (at least for now).
120mm x 60mm x 40mm should create the general shape of the mouse.
Using a fully right view of a gaming mouse and a symmetry line down the center of the box, I could now start sculpting the mouse's shape.

![Iteration 1]({{site.baseurl}}/assets/img/LowProfileMouse1.jpg)

Once the mouse shape was appropriate, I wanted to smooth the curves. 

![Iteration 2]({{site.baseurl}}/assets/img/LowProfileMouse2.jpg)

The box started to look more like a nice car, which let me know I was headed in the right direction.

![Iteration 3]({{site.baseurl}}/assets/img/LowProfileMouse3.jpg)

Now it came time to hollow out the body. Duplicating the body and shrinking one of them down to cut a smaller version of the mouse, allows the internals to have a flat bottom, and the sides to maintain their ergonomics.

![Iteration 4]({{site.baseurl}}/assets/img/LowProfileMouse4.jpg)

Checking the Cross sectional area let me know that it was at least manufacturable. Checking between the two thinnest surfaces displayed that ~1mm of thickness was the thinnest point. For what this model was going to be used for, this was appropriate, however the lowest I'd go would be 1.75mm thickness.

![Iteration 5]({{site.baseurl}}/assets/img/LowProfileMouse5.jpg)

Now came time to start separating the bodies. Creating the Left and Right Mouse Buttons

![Iteration 6]({{site.baseurl}}/assets/img/LowProfileMouse6.jpg)

Initially, this layout seemed fine, but when thinking about the function a mouse has and the arc the mouse buttons have to progress through, I knew that I had to move the Left and Right Mouse Buttons forward and closer together such that they had free space to move up and down and only the outside frame to contain them.

![Iteration 8]({{site.baseurl}}/assets/img/LowProfileMouse8.jpg)

Now it's really starting to look like a mouse, the retaining body for the Left and Right Mouse buttons has some sharp edges, but to get a general understanding, this would do.

![Iteration 10]({{site.baseurl}}/assets/img/LowProfileMouse10.jpg)

I wanted to create internal markings on where I thought the On/Off switch, CMOS Sensor and Bluetooth button would go. These few components could fit roughly in the center of the mouse and leave space for the left and right switches along with some weights in the back of the mouse for a good feel in the hand.

![Iteration 11]({{site.baseurl}}/assets/img/LowProfileMouse11.jpg)

Now it was time to experiment with mouse buttons. I wanted to create a 3 button right-handed mouse that would allow the thumb to press any of the three buttons whenever it was needed and while I think this would be valuable to some gamers, it would also require a special set of switches that aren't very common on current gaming mice setups.

![Iteration 13]({{site.baseurl}}/assets/img/LowProfileMouse13.jpg)
![Iteration 14]({{site.baseurl}}/assets/img/LowProfileMouse14.jpg)

Now that the LC, RC, MB1, MB2, MB3 were all created, it was now time to create a top and bottom for the mouse to connect. a simple fit point spline and body split, created an upper and lower body.

![Iteration 16]({{site.baseurl}}/assets/img/LowProfileMouse15.jpg)

Here it is, the first set of renders for this gaming mouse concept - simple and ergonomic no LED placements, but the general concept was created. Now it's time to buy a mouse off of Amazon and really design around the electronics.
The Razer DeathAdder Essential Gaming Mouse has a hefty 33% off deal along with overnight shipping - making it the perfect candidate for ariving and cannibalizing before 6:30pm tomorrow.

![Iteration 16]({{site.baseurl}}/assets/img/LowProfileMouse16.jpg)

## Gaming Mouse Design

Now that I have the mouse I'm going to cannibalize ordered, I can get some of the auxillary pieces started and save myself some time before having to design the PCB + components when the mouse arrives.

First, I got to sketching out the adjusted gaming mouse, and logo that will be etched on the back.

![Final Mouse 1]({{site.baseurl}}/assets/img/GamingMouseSketch.jpg)

Once I got a design that I thought was appropriate, I moved the Logo over to Illustrator and made an SVG file for easy import into Fusion.

![Final Mouse 2]({{site.baseurl}}/assets/img/GamingMouseLogo.jpg)

A few adjustments later, and here's the final logo.

![Final Mouse 3]({{site.baseurl}}/assets/img/GamingMouseLogoFinal.jpg)

I created a simple template that outlines my planned mouse using correct dimmensions, this will save me a bit of work tomorrow and allows me to plan the design in advance. I also went ahead and designed the buttons and thumbpad which will need to be adjusted depending on the PCB design and the corresponding space requirements.

![Final Mouse 4]({{site.baseurl}}/assets/img/GamingMouseAccessories.jpg)


