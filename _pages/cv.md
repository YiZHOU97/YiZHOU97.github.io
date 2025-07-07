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
* Ph.D. in Mechanical Engineering, Hong Kong University of Science and Technology, 2022-now
* MSC. in Mechanical and Automation Engineering, The Chinese University of Hong Kong, 2021-2022
* B.E. in Aircraft Design and Engineering, Northwestern Polytechnical University, 2016-2020

Work experience
======
* Research Assistant
  * National University of Singapore
  * Duties included: 
    * Realtime control system establishment 
    * Compliant control deployment

* Software Engineer Internship
  * XYZ Robotics Inc.
  * Duties included: Motion control of industrial robots
  
Skills
======
* Python, C++, Matlab, Simulink, PLC
* Beckhoff TwinCAT, Solidworks, ANSYS
* Embedded development

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->