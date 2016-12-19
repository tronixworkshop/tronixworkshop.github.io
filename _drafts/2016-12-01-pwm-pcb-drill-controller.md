---
layout:  post
title: 555 Timer PWM 18V Mini PCB Drill Speed Controller
date: 2016-11-28
dateModified: 2016-12-01
author: Andrew Devanney
image: /images/drill-controller/drill-controller.jpg
category: projects
tags: [555, pwm]
permalink: /archive/555-timer-pwm-drill-controller/
github: 'https://github.com/tronixworkshop/tronixworkshop.github.io'
---

A simple circuit comprising of a 555 timer and a power mosfet to control the speed of a mini PCB drill.
<!--more-->

<!-- {% include download-button.html url = page.github %} -->

## Introduction
 One of the tools my workshop needed was a pcb drill speed controller, since I seemed to have lost my original controller that came with the drill. The circuit wouldn't need to be over complicated since a simple 555 timer and a power mosfet would be enough to send a PWM signal to the drill to control its speed.

 ![The full setup, with drill, controller and stand][drill-controller]

### The Circuit
The 555 timer is wired in an astable configuration meaning the output is constantly switching on and off generating a square wave signal. Adjusting the square wave output should allow us to change the time on (tON) and time off (tOff), the duty cycle, or what is commonly referred to as pulse width modulation (pwm).

This circuit is using a common astable configuration to generate a simple pulse, which can be modified using a 100k ohm potentiometer

A potentiometer (100k) is employed to adjust the duty cycle to alter the speed of the drill. An Additional 18V Power and the potentiometer are connected through screw terminals.

![Schematics diagram of my 555 timer PCB drill controller][schematics]

![Eagle PCB of my 555 timer PCB drill controller][pcb]

<!-- <figure class="figure">
  <img src="/images/drillcontroller_rev02_pcb.png" alt="">
  <figcaption class="figure-caption">Drill Controller Rev 2 PCB</figcaption>
</figure> -->

{% include component-listing.html title='drill-controller-rev2' table-data = site.data.drill-controller %}

[schematics]:/images/drill-controller/drillcontroller_rev02_sch.png "schematic of my 555 timer pulse width 18v PCB drill controller"
[pcb]:/images/drill-controller/drillcontroller_rev02_pcb.png "Bottom layer PCB drawing of my 555 timer pulse width 18v PCB drill controller"
[drill-controller]:/images/drill-controller/drill-controller-stand.jpg "The full setup, with drill, controller and stand"
