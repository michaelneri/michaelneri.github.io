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
* Ph.D in Applied Electronics, Roma Tre University, 2025 (expected). Thesis: "Scene Understanding with Sound using Artificial Intelligence Techniques" under the supervision of Prof. Marco Carli and Prof. Alessandro Neri.
* M.Sc. in ICT for Internet and Multimedia, University of Padua, 2021. Thesis: "Pointcloud object detection and classification for railway applications" under the supervision of Prof. Federica Battisti.
* B.Sc. in Information Engineering, University of Padua, 2019. Thesis: "Monitoring of network resources using Nagios Core Application" under the supervision of Prof. Andrea Zanella.

Work experience
======
* Summer 2021: Artificial Intelligence Engineer
  * RadioLabs, Consorzio Università Industria – Laboratori di Radiocomunicazioni.
  * Deep learning techniqes for 3D object detection in point clouds (M. Sc. Thesis).

* 2016 - 2018: IT Intern
  * Gruppo Battistolli S.p.A.
  * IT Help desk, network resources monitoring with Nagios Framework (B. Sc. Thesis).

  
Skills
======
* Programming Languages: Python, Java, JavaScript, Matlab, C#, C++, LaTeX
* Strong theoretical background regarding Machine Learning, Deep Learning, and Neural Networks.
  * Audio processing with Artificial Intelligence Techniques.
  * Advanced knowledge of Pytorch, Keras, Tensorflow.
* Knowledge of Telecommunications networks.

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
  
