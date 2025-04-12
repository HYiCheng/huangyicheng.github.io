---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Integrated Circuit, Beihang University, 2023.09 - 2026.01 (expected)
* B.S. in Microelectronics, Southwest Jiaotong University, 2019.09-2023.06

<!--
Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  注释掉了
  -->

Skills
======
* Programming Language: C, Verilog, Python
* IC Design: Design Complier, VCS, Verdi, Modelsim, Spyglass, ···
* Embedded System
  * Hardware: PCB design and Layout with Altium Designer 
  * Software: MCU (like STM32, ESP32), FPGA (AMD&Xilinx Vitis, AMD&Xilinx Vivado and Intel&Altera Quartus)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!--
Service and leadership
======
* Currently signed in to 43 different slack teams
  注释掉了
-->
