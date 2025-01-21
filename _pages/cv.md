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
* **2016.09 - 2022.03**, Ph.D., State Key Laboratory for Strength and Vibration of Mechanical Structures, Multiscale Mechanics and Medical Science Lab, Department of Engineering Mechanics, School of Aerospace, Xi'an Jiaotong University, Xian, China.
* **2020.01 - 2021.03**, Visiting scholar, Earth and Environmental Engineering Department, Columbia University, Xian, China.
* **2012.09 - 2016.06**, Bachelor, Aircraft Design and Engineering, Xi'an, Shaanxi, China.

Work experience
======
* Sep 2022: Assistant Prof
  * Department of Engineering Mechanics
  * Xi'an Jiaotong University
  * Xi'an, China

Skills
======
* Machine Learning (Pytorch, Python...)
* Academic Writing (Office, Visio, Origin, Endnote)
* Multiscale Modeling
  * DFT (VASP, Quantum ESPRESSO, CASTEP)
  * MD (Lammps, Gromacs)
  * FEM (Abaqus, LS-Dyna, COMSOL, FEniCS)
  * PF (Phase field crystal, Phase field fracture)

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
  
