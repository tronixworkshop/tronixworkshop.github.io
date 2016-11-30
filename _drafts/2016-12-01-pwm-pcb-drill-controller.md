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

Another tool my shop needed was a pcb drill speed controller since I seemed to have lost my original controller that came will my drill. The circuit wouldn't need to be over complicated since a simple 555 timer and a power mosfet would be enough to send a PWM signal to the drill to control its speed.

### Circuit operation

So here goes the 555 is wired in an astable configuration meaning the out is constantly switching on and off, a square wave the controls should allow us to change the time on (tON) and time off (tOff), the duty cycle, thus creating what is commonly known as pulse width modulation (pwm).

![555 timer PCB drill controller][schematics]

<figure class="figure">
  <img src="/images/drillcontroller_rev02_pcb.png" alt="">
  <figcaption class="figure-caption">Drill Controller Rev 2 PCB</figcaption>
</figure>

{% include component-listing.html title='drill-controller-rev2' table-data = site.data.drill-controller %}


[schematics]:/images/drillcontroller_rev02_sch.png "555 timer pulse width 18v PCB drill controller"
