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
* M.S. in Information Technology and Electrical Engineering, ETH Zürich, 2025 (expected)
* B.S. in Data Science, Universitat Politècnica de Catalunya, 2023
* B.S. in Engineering Physics, Universitat Politècnica de Catalunya, 2023

Work experience
======
* Spring 2024: Research Assistant
  * ETH Zürich, Switzerland
  * Duties included: Compiler Development for High-Level Synthesis
  * Supervisor: Prof. Dr. Lana Josipovic

* Fall 2022 - Spring 2023: Research Intern
  * Netflix, Los Gatos, USA
  * Duties included: Development of Video Coding Algorithms
  * Supervisor: Dr. Joel Sole

* Summer 2022: Engineering Intern
  * Qualcomm, remote, USA
  * Duties included: Deep Learning for Network Planning
  * Supervisor: Dr. Jordi Ros-Giralt


Skills
======
* Programming Languages
  * C++
  * C
  * Python
  * SIMD (x86 and AVX)
* Deep Learning
  * Pytorch
  * OpenCV
* Cloud Computing
  * AWS EC2
  * Google Cloud Vertex AI

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
  
