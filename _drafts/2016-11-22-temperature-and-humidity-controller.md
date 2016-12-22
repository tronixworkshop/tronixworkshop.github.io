---
layout: post
title:  Workshop Temperature and Humidity Controller
date:   2016-11-28
dateModified: 2016-11-28
author: Andrew Devanney
image:
category: projects
tags: [measurements, arduino]
permalink: /arduino-temperature-humidity-controller-part1/
---


<!--more-->

## Design and prototype

With typical British weather we need to maintain the temperature in the workshop, but I wanted to create the controller myself rather than just buying a digital thermostat and wiring that to a heater, where's the fun in that - also it solve a couple problems, my PCB equipment had been in storage for some time, in a cellar, and had travelled around to different houses over the years. It was a good idea to test this stuff out on something simple, plus my electronics skills have diminished, and I've gotten rusty.

The idea was simple, the controller would use a micro-controller to monitor the average temperature over a fixed amount of time and given a typical set of upper and lower set points engage a solid state relay to active a heater or disengage if cooling down. The trouble with this plan is you will always need to adjust the settings due changes in the weather, so I needed to add an additional menu to make changes to any predefined settings. Making the controller Arduino based makes it very simple to get going, it would however create certain limitations on future challenges, but this is a simple temperature controller, no need to pull out the big guns just yet! I'm a little rusty with the microchip toolchain these days and the pic16f84 has had its day, so i wanted to make the project relevant enough that other beginners would find it useful. This can easily be modified to control any kind of heater due the use of a solid state relay.

The ATmega328p uses a MAX7219 LED Display Driver to drive a seven segment display using the SPI bus to communicate. The temperature and humidity are read from a ds11 sensor and is averaged over several reads to reduce the noise.

The micro first reads the temperature and humidity sensor and display this reading on the seven segment, the value is compared to the upper and lower set point value and the result logic with activate the solid state relay.

The set points can be adjusted by adjusting the digital encoder, the micro will detect any changes made and put the controller into menu state, once in menu state the display with flash first the upper limit and clicking the button on the encoder will switch to the lower limit.
