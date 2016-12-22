---
layout:  post
title: 555 Timer PWM 18V Mini PCB Drill Speed Controller
date: 2016-12-01
dateModified: 2016-12-22
author: Andrew Devanney
image: /images/drill-controller/drill-controller-stand.jpg
category: projects
tags: [555, pwm]
permalink: /archive/555-timer-pwm-drill-controller/
github: 'https://github.com/tronixworkshop/tronixworkshop.github.io'
---

A simple circuit comprising of a 555 timer and a power mosfet to control the speed of a mini PCB drill.
<!--more-->

<!-- {% include download-button.html url = page.github %} -->

## Introduction
 One of the tools my workshop needed was a pcb drill speed controller, since I have lost my original controller that came with the drill. The circuit wouldn't need to be over complicated since a simple 555 timer and a power mosfet to drive it at 18v would be enough to send a PWM signal to the drill to control its speed.

 ![The full setup, with drill, controller and stand][drill-controller]

### The Circuit
This controller circuit generates a PWM signal to control the drill speed, it uses a 555 timer in astable configuration. The duty cycle, or on/off time, can be modified by adjusting the 100k ohm potentiometer connected through screw terminals (X2), thus changing the drills speed. The mini drill requires an 18v supply and this is driven though Q2 IRF540 mosfet to separate the load voltage from the 5v supply voltage that is used for the rest of the circuit.

![Schematics diagram of my 555 timer PCB drill controller][schematics]
![Eagle PCB of my 555 timer PCB drill controller][pcb]

<!-- <figure class="figure">
  <img src="/images/drillcontroller_rev02_pcb.png" alt="">
  <figcaption class="figure-caption">Drill Controller Rev 2 PCB</figcaption>
</figure> -->

{% include component-listing.html title='drill-controller-rev2' table-data = site.data.drill-controller %}

[schematics]:/images/drill-controller/drillcontroller_rev02_sch.png "schematic of my 555 timer pulse width 18v PCB drill controller"
[pcb]:/images/drill-controller/drillcontroller_rev02_pcb.png "Bottom layer PCB drawing of my 555 timer pulse width 18v PCB drill controller"
[drill-controller]:/images/drill-controller/drill-controller.jpg "The full setup, with drill, controller and stand"
