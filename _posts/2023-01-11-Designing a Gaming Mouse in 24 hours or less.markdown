---
layout: post
title: "Designing a Gaming mouse in 48 hours or less."
date: 2023-01-11 20:45:00 
description: Ergonomic Gaming Mouse Design
img: MouseHeroImage.jpg
tags: [Gaming,Design,3D-Printing,Engineering]
---

## The overall goal of this project was to design a functional gaming mouse in 48 hours. 
Gaming mice differ from normal computer mice, in that they are designed to be used at a much higher frequency to normal mice, they are rated for higher amounts of clicks, have higher or more customizable DPI (dots per inch) and often contain RGB (Red Green Blue) strips that are customizable.

## Design-specific goals:
- The mouse should have a two part shell that houses the PCB from a Razor Death Adder

- The shell should have a contour that makes lifting the mouse easier.

- The mouse should have 5 buttons total, MB1, MB2, LC, RC, Scroll Wheel Button 

- The mouse buttons should be easily pressable by the thumb

- The mouse should have guard-less left and right clicks

- The mouse should be corded

- The fasteners + pads from the Razor Death Adder should be used to connect the bodies of the mouse.

- 3D print the body and base, then put it all together

## Start time: 6:30pm January 11th, 2023

## Proof of Concept
Time to make a **really rough sketch** to remember basic functions I'm going to be adding in.

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

Here it is, the first set of renders for this mouse concept - simple and ergonomic no LED placements, but the general concept was created. Now it's time to buy a mouse off of Amazon and really design around the electronics.
The Razer DeathAdder Essential Gaming Mouse has a hefty 33% off deal along with overnight shipping - making it the perfect candidate for ariving and cannibalizing before 6:30pm tomorrow.

![Iteration 16]({{site.baseurl}}/assets/img/LowProfileMouse16.jpg)

## Gaming Mouse Design

Now that I've ordered the mouse I'm going to cannibalize and completed a quick sample mouse, I can get some of the auxillary pieces started and save myself some time before having to design the PCB + components when the mouse arrives.

First, I got to sketching out the adjusted gaming mouse and logo that will be etched on the back.

![Final Mouse 1]({{site.baseurl}}/assets/img/GamingMouseSketch.jpg)

Once I got a design that I thought was appropriate, I moved the Logo over to Illustrator and made an SVG file for easy import into Fusion.

![Final Mouse 2]({{site.baseurl}}/assets/img/GamingMouseLogo.jpg)

A few adjustments later, and here's the final logo.

![Final Mouse 3]({{site.baseurl}}/assets/img/GamingMouseLogoFinal.jpg)

I created a simple template that outlines my planned mouse using correct dimmensions, this will save me a bit of work tomorrow and allows me to plan the design in advance. I also went ahead and designed the buttons and thumbpad which may need to be adjusted depending on the PCB design and the corresponding space requirements.

![Final Mouse 4]({{site.baseurl}}/assets/img/GamingMouseAccessories.jpg)

Unfortunately, the Razer Mouse didnt arrive early the next day when it was supposed to, instead it arrived at 6:30pm, but that was fine. I took the time to develop a general shape for the mouse body. 

![Final Mouse 5]({{site.baseurl}}/assets/img/GamingMouse1.jpg)

Since I didn't have the PCB from the Death Adder, I went ahead and printed the mouse to compare with what I currently have, a Logitech G Pro. Clearly, the body wasn't wide enough, but the thumb and ring finger contours were awesome.

![Final Mouse 6]({{site.baseurl}}/assets/img/GamingMouse2.jpg)

After widening the base a little bit, I reprinted the full mouse this time. It felt good, and really encompassed the body shape I was looking for.

![Final Mouse 7]({{site.baseurl}}/assets/img/GamingMouse3.jpg)

The mouse arrived! Now it's time to design the PCB. Since this was a 48 hour challenge, I only designed the critical components.

![Final Mouse 8]({{site.baseurl}}/assets/img/GamingMouse4.jpg)

Now that the PCB was completed, I could slot it inside the base of the mouse and work on critical functionality - Mouse clicks, and wire routing. The setup, was to hide the wire underneath the PCB, since it's a tight space and the CMOS sensor already required the board to be elevated, this made sense to keep the mouse width normal.

![Final Mouse 9]({{site.baseurl}}/assets/img/GamingMouse5.jpg)

Now came time to create the top of the mouse. The switches for left and right click needed to be pressed, which means the top body had to have a way to create a fulcrum for the buttons. a simple cut across the body created a separation point and a good way to convert your presses, into clicks. MB1 and MB2 were created on the side, with 0.4mm spacing to ensure the throw wouldn't interfere with the main body. 

![Final Mouse 10]({{site.baseurl}}/assets/img/GamingMouse6.jpg)

Now it came time to add spaces for fastening. Because of space limitations I had to secure the top and bottom pieces at the front of the mouse, which is not ideal from an asthetics standpoint, but time was running out and redesigning the mesh body was going to cause so many things to need rework so I had to make the concession. 

![Final Mouse 11]({{site.baseurl}}/assets/img/GamingMouse7.jpg)

Adding some additional supports to the mouse upper body around the connection holes and fillets around the Leftclick + right click bases helps with 3D printing and making sure the components can support longer term use.

![Final Mouse 12]({{site.baseurl}}/assets/img/GamingMouse8.jpg)

One last fit test!

![Final Mouse 20]({{site.baseurl}}/assets/img/GamingMouseAssembly.gif)

Here's the finished model!

![Final Mouse 13]({{site.baseurl}}/assets/img/GamingMouseDesignv12.gif)

and some renders!

![Final Mouse 15]({{site.baseurl}}/assets/img/Gaming MouseFinal.jpg)

![Final Mouse 16]({{site.baseurl}}/assets/img/GamingMouseFinal2.jpg)

![Final Mouse 18]({{site.baseurl}}/assets/img/GamingMouseFinal4.jpg)

![Final Mouse 17]({{site.baseurl}}/assets/img/GamingMouseFinal3.jpg)

There is a lot that could be improved in this design, but I'm glad I got a functioning mouse at the end of it. 

![Final Mouse 19]({{site.baseurl}}/assets/img/GamingMouseFinalVideo.gif)

## Completion time: 5:26pm January 13th, 2023 - Total elapsed time, 47 hours


