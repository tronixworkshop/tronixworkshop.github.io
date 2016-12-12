---
layout:  post
title: 555 Timer PWM 18V Mini PCB Drill Speed Controller
date: 2016-11-28
dateModified: 2016-12-01
author: Andrew Devanney
image:
category: projects
tags: [555, pwm]
permalink: /archive/555-timer-pwm-drill-controller/
github: 'https://github.com/tronixworkshop/tronixworkshop.github.io'
---

<!--more-->

{% include download-button.html url = page.github %}

## Introduction
A simple circuit comprising of a 555 timer to control the speed of a PCB drill. One of the tools my workshop needed was a pcb drill speed controller, since I seemed to have lost my original controller that came with the drill. The circuit wouldn't need to be over complicated since a simple 555 timer and a power mosfet would be enough to send a PWM signal to the drill to control its speed.

### The Circuit

The 555 timer is wired in an astable configuration meaning the output is constantly switching on and off generating a square wave signal. Adjust the signal should allow us to change the time on (tON) and time off (tOff), the duty cycle, thus creating what is commonly known as pulse width modulation (pwm).

This is a common astable configuration, a variable resistor is employed to adjust the duty cycle to alter the speed of the drill. 18V Power and the variable resistor are connected through screw terminals.


Additional Components
18V DC Power Adapter
100K Ohm Variable resistor
Small project enclosure

![555 timer PCB drill controller][schematics]

<figure class="figure">
  <img src="/images/drillcontroller_rev02_pcb.png" alt="">
  <figcaption class="figure-caption">Drill Controller Rev 2 PCB</figcaption>
</figure>

{% include component-listing.html title='drill-controller-rev2' table-data = site.data.drill-controller %}


[schematics]:/images/drillcontroller_rev02_sch.png "555 timer pulse width 18v PCB drill controller"
