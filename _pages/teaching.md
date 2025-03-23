---
layout: page
title: teaching
permalink: /teaching/
courses:
  - title: EE 271 (Autumn 2024)
    description: Introduction to digital computer systems, covering digital logic, Boolean algebra, combinational and sequential circuit design, binary number systems, and programmable logic devices.
  - title: EE 201 (Spring 2025)
    description: A lab-focused course introducing fundamental hands-on skills essential for electrical and computer engineers. Covers key topic areas like circuit construction, microcontroller programming, PID control, soldering, circuit simulation, 3D design and printing, PCB development, and sensor integration.
nav: true
nav_order: 6
---


{% for course in page.courses %}
### {{ course.title }}

{{ course.description }}

{% endfor %}

<!-- 

For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->
