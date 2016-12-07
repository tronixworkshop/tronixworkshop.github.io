---
layout: post
title:  Hypercube 3D Printer Build Part 1
date:   2016-11-28
dateModified: 2016-11-28
author: Andrew Devanney
image:
category: projects
tags: [hypercube, 3dprinter]
permalink: /how-to-build-a-3dprinter-part1/
---

One of the most exciting projects to build is a 3D printer, I have always wanted to build one as soon as heard about them.  I have followed a lot of different designs over the years and had almost committed to buying a new Prusa MK2 kit before deciding to build my own. This project bring a lot of different skills together, while complicated its also extremely obvious at the same time.
<!--more-->

## Introduction
The design I chose to build is called the [HyperCube] and was designed By [Tech2c on YouTube], I really liked this design because of its simplicity while still fulfilling the requirements of a great 3D printer. This build is based on a [CoreXY] design, uses a cantilever Z axis for the bed, and the X gantry uses a light weight anodised Aluminium tube instead of solid steels ones. The frame of the printer is built with T-Slot Aluminium extrusion and T-Slot nuts making assembly extremely simple. The aluminium was bought in 1.5 meter lengths and cut down to size to save a little money, I was happy to follow Tech2c exact method of cutting this extrusion using a metre block, which turned out with precise results.

 -- insert image of cutting set up

The cut down extrusion pieces are fastened together with aluminium corner brackets, the combination of the T-Slot nuts and these corner brackets make for a really solid frame.
(EXPAND)

 -- insert image of complete frame

My 3D printed parts were printed by a local printer I found on 3DHubs called [chunky-steveo], 3dhubs is an excellent service and is great if you don't have access to a printer but need prints for your design, it solved my catch 22 problem when build this printer. The parts took about 10 days to discuss, negotiate a price, print and ship, there is 41 parts in total for this design.

I've documented my progress so others can learn and follow the build, this is also useful for myself to refer back to.

Step 1 cut the extrusion lengths to size
Step 2 build the frame with corner brackets, and build the bed
Step 3 attach the shaft clamps to hold the steel smooth rod, note: the left motor mount.
Step 4 build the x carriage from y/y joiners and aluminium tube
Step 5 attach the x gantry/carriage
Step 6 attach motor mounts and stepper motors
Step 7 attach the belts
Step 8 check the movements - left motor anti-clockwise move x/y gantry to upper right
step 9 attach the Z axis bed to the frame
step 10 solder the wires to the heat bed and attach the thermistor
step 11 attach the aluminium heat bed
Step 12 attach the end stops
step 13 attach the E3D v6 hot end assembly
step 14 attach the extruder and PTFE tube
step 15 wire up the Arduino and Ramps and install Marlin
step 16 check wiring through pronterface
step 17 level the bed with the hot end
step 18 print a test cube




[HyperCube][1]

[HyperCube]: http://www.thingiverse.com/thing:1752766
[Tech2c on YouTube]: https://www.youtube.com/playlist?list=PLIaArjwViQRVAERWRrYfe9rtiwvvRGCzw
[CoreXY]: http://corexy.com/theory.html
[chunky-steveo]:https://www.3dhubs.com/manchester/hubs/chunky-steveo

Notes: -

useful links
http://makezine.com/projects/the-makergear-mosaic-3d-printer-part-viii-the-first-print/

Frame:
T-Slot 2020 Aluminium Extrusion Profiles for X200 x Y200 x Z155 print bed area

4 x 340mm (X) = 1360 (135)
4 x 303mm (Y) = 1212 (283)
4 x 350mm (Z) = 1400 (95)
2 x 285mm (Bed) = 570 (925)
1 x 135mm (Bed)
