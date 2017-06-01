---
layout: post
title:  Building the Hypercube 3D Printer Part 1
date:   2017-06-01
dateModified: 2017-06-01
author: Andrew Devanney
image: /images/hypercube-3dprinter/xy-assembly-fitted.jpg
category: projects
tags: [hypercube, 3dprinter]
permalink: /building-hypercube-3dprinter-part1/
---

Last November (2016) I started building my first project in the workshop, the HyperCube 3d printer. Its been a struggle to complete this post after becoming a father for the second time in January.

3d printers are a great tool to rapidly prototype designs cheaply and easily, building your own printer can be quite challenging, but its something I've always wanted to do. I found a design online that was both cheap a easy to build. This will be the start of the a series of posts following my build.
<!--more-->

## Introduction

The printer I chose to build is called the [HyperCube] and was designed By [Tech2c on YouTube], I really liked this design because of its simplicity while still fulfilling the requirements of a great 3D printer. This build is based on a [CoreXY] design, uses a cantilever Z axis for the bed, and the X axis uses light weight anodised aluminium tubes instead of solid steels ones. The frame of the printer is built with T-Slot aluminium extrusion and T-Slot nuts making assembly extremely simple. The aluminium was bought in 1.5 meter lengths and cut down to size to save a little money, I was happy to follow Tech2c exact method of cutting this extrusion using a mitre block, which turned out with precise results.

### Frame construction

The aluminium extrusion was down to the correct lengths needed, see table, using a mitre block this kept the aluminium stable and the results were quite precise only a small amount of filing was needed to de-burr and smooth the rough edges.

![20 X 20 aluminium extrusion][extrusion]
*20 X 20 aluminium extrusion*

{:.table .table-bordered .table-striped}
| Qty    | Dimension | Length   |
| :----: | :-------- | :---------
| 4      | X         | 340 mm   |
| 4      | Y         | 303 mm   |
| 4      | Z         | 350 mm   |
| 2      | Bed       | 285 mm   |
| 1      | Bed       | 135 mm   |

Printer Frame:
T-Slot 2020 Aluminium Extrusion Profiles for X200 x Y200 x Z155 print bed area

![cutting aluminium extrusion with the mitre block][cutting-setup]
*Cutting aluminium extrusion with the mitre block*

The aluminium extrusion used for the frame build was a slightly different type from the one Tech2c used in his build, the type I acquired was listed as type-I slot 5, this was lost on me, it meant 5 mm slot. The t-slot nuts used required a 6mm slot, this still works ok, however the nuts don't drop straight in, there's a slight knack to getting them in and to horizontally lay flat in the T-slot.

![stopping scratches with masking tape][protecting-with-tape]
*Stopping scratches with masking tape*

The aluminium was easily scratched, so i covered the lengths in masking tape to protect while it was cut to size.

![all frames pieces cut to size][cut-to-length]
*All frames pieces cut to size*

The cut down extrusion pieces were fastened together with aluminium corner brackets, the combination of the T-Slot nuts and these corner brackets make for a really solid frame. I first built up two of the side squares using 340mm for X and 350mm for Z and then using aluminium corner brackets to join the lengths together.

![a single side frame][single-frame]
*A single side frame*

Once the two frames were constructed these were joined together again with two corner brackets to the Y 303mm lengths of extrusion. The two frames were checked with a try square for any deviation in the corner brackets and extrusion cuts that may have cause variations in the cube.

![two single side frames][two-frames]
*Two single side frames*

### 3d Printed Parts

My 3D printed parts were printed by a local printer I found on 3DHubs called [chunky-steveo], 3dhubs is an excellent service and is great if you don't have access to a printer but need prints for your design, it solved my catch 22 problem when building this printer. The parts took about 10 days to discuss, negotiate a price, print and ship, there is 41 parts in total for this design and these prints are flawless.

![my printed parts][printed-parts]
*My printed parts*

### Attaching Y axis

Once these two frames are joined together the y axis brackets and axis steel rods could be fitted to the frame, remembering to also add a LM8UU bearings to the steel rod. The front left Y axis bracket is shared by the left stepper motor holder, so I left the fixing loose until the motor holder was ready to fit.

![fitting the Y axis to the frame][y-axis-and-xy-assembly]
*Fitting the Y axis to the frame*

![Y axis fitted to the frame with the bearings][y-axis-fitted]
*Y axis fitted to the frame with the bearings*

### Assembling the X carriage

The XY joiners need 2 F623ZZ flange bearings with a 20mm m3 hex screw and a m3 nyloc nut. The anodised aluminium rods are clamped in place with 20mm m3 screws as well.  

![XY joiners assembly][xy-joiners]
*XY joiners assembly*

To assemble the X carriage brass bushing are inserted into the bushing holders and screwed to the X carriage frame, this carriage slides along the anodised aluminium rods. The XY joiners along with two 360mm anodised aluminium rods and the X carriage creates the X carriage assembly.

![The completed XY assembly - front][xy-assembly-front]
*The front of the completed XY assembly*
![The completed XY assembly - back][xy-assembly-back]
*The back of the completed XY assembly*

When the x carriage assembly has been constructed it's time to attached it to the y axis bearings. This part was the most time consuming aspect of this design, the XY joiner covers if overtightened may cause the carriage to skew slightly.

![XY assembly fitted to the Y axis][xy-assembly-fitted]
*XY assembly fitted to the Y axis*

To overcome this I first attached the carriage to the bearings and adjusted for the best travel and smoothness to see if any binding was present. Adjusting and turning the x axis anodised aluminium tubes seemed to free up the x carriage at this point the tubes can be clamped slightly to prevent movement. At this point the y axis cover can be attached and tightened equally slowly to ensure an even fit.

### Idlers and steppers motor holders

![setting up the idlers][idlers-setup]
*Setting up the idlers*

The next step assemble and fit the idlers, which consists of four F623ZZ flange bearings sandwiched together, 35mm m3 screw and nyloc nut.

![the completed idlers][idlers]
*The completed idlers*

The idlers fit to the back of the frame with their bearings facing inwards.

![the idlers fitted to the frame][idlers-fitted]
*The idlers fitted to the frame*

The stepper motor holder are fitted to the front of the frame with the right (Y) motor holder slightly lower than the left (X) motor holder.

![the left and right motor holders][motor-brackets-fitted]
*The left and right stepper motor holders*

The holders simply push up to the Y axis brackets. The left holder uses the bottom fixing of the left Y axis bracket.

![the left (X) stepper motor holder and the Y axis bracket][x-motor-bracket-fitted]
*The left (X) stepper motor holder and the Y axis bracket*

The right holder just pushes against the end of the Y axis holder

![the right (Y) stepper motor][y-motor-bracket-fitted]
*The right (Y) stepper motor*


### Attaching the Z axis

The z axis was pretty easy to fit, once the steel rod holders were fitted the steel rods simply slotted through the holes, I left them loose at this point, since I didn't know what the exact measurements from the bed would be.

![fitting the Z axis brackets][z-axis-bracket-fitted]
*Fitting the Z axis brackets*
![completed Z axis with 350mm 8mm steel rods][z-axis-fitted]
*Completed Z axis with 350mm 8mm steel rods*


[HyperCube]: http://www.thingiverse.com/thing:1752766
[Tech2c on YouTube]: https://www.youtube.com/playlist?list=PLIaArjwViQRVAERWRrYfe9rtiwvvRGCzw
[CoreXY]: http://corexy.com/theory.html
[chunky-steveo]:https://www.3dhubs.com/manchester/hubs/chunky-steveo

[extrusion]:/images/hypercube-3dprinter/extrusion.jpg "20x20 aluminium extrusion"
[cutting-setup]:/images/hypercube-3dprinter/cutting-setup.jpg "cutting extrusion in mitre block"
[protecting-with-tape]:/images/hypercube-3dprinter/protecting-with-tape.jpg "protecting the aluminium with masking tape"
[cut-to-length]:/images/hypercube-3dprinter/extrusion-cut-down.jpg "extrusion cut to required lengths"
[single-frame]:/images/hypercube-3dprinter/single-frame.jpg "constructing a single side frame"
[two-frames]:/images/hypercube-3dprinter/two-frames.jpg "two side frames completed"
[printed-parts]:/images/hypercube-3dprinter/printed-parts.jpg "my printed parts"

[y-axis-fitted]:/images/hypercube-3dprinter/y-axis-fitted.jpg "y axis fitted to printer frame"
[y-axis-and-xy-assembly]:/images/hypercube-3dprinter/y-axis-and-xy-assembly.jpg "y axis and the xy joiner assembly"


[xy-joiners]:/images/hypercube-3dprinter/xy-joiners.jpg "making the xy joiners"
[xy-assembly-front]:/images/hypercube-3dprinter/xy-assembly-front.jpg "xy assembly assembled"
[xy-assembly-back]:/images/hypercube-3dprinter/xy-assembly-back.jpg "xy assembly assembled"
[xy-assembly-fitted]:/images/hypercube-3dprinter/xy-assembly-fitted.jpg "two side frames completed"

[idlers]:/images/hypercube-3dprinter/idlers.jpg "fitting the idlers"
[idlers-setup]:/images/hypercube-3dprinter/idlers-setup.jpg "making the idlers"
[idlers-fitted]:/images/hypercube-3dprinter/idlers-fitted.jpg "fitting" the idlers"
[motor-brackets-fitted]:/images/hypercube-3dprinter/motor-brackets-fitted.jpg "motor brackets fitted"

[y-motor-bracket-fitted]:/images/hypercube-3dprinter/y-motor-bracket-fitted.jpg "y axis stepper motor brackets (right side)"
[x-motor-bracket-fitted]:/images/hypercube-3dprinter/x-motor-bracket-fitted.jpg "x axis stepper motor brackets (left side)"
[z-axis-bracket-fitted]:/images/hypercube-3dprinter/z-axis-brackets-fitted.jpg "z axis bracket fitted"
[z-axis-fitted]:/images/hypercube-3dprinter/z-axis-fitted.jpg "z axis fitted"
