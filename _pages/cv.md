---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**Master of Science (M.Sc.) in Chemistry**  
Indian Institute of Technology Roorkee, India  
Specialization: Physical and Computational Chemistry

**Bachelor of Science (B.Sc. Honours) in Chemistry**  
University of Delhi, India  
Focused on molecular chemistry, solid-state chemistry, and quantum mechanics.

## Research Experience

* **IISc Bangalore** — Computational Studies on Borane Clusters (Supervisor: Prof. E. D. Jemmis)
* **IIT Roorkee (Master's Thesis)** — Thermoelectric Properties of Half-Heusler CoTiSb (Supervisor: Prof. H. Kandpal)
* **Ashoka University** — DFT Investigation of Fe-Pincer Catalysts for Hydrogen Production (Supervisor: Prof. V. Avasare)
* **IIT Delhi** — Low-Dimensional and Hybrid Materials Modelling (Supervisor: Prof. N. Ray)

## Technical Skills

* **Electronic Structure Methods:** DFT, ab-initio molecular dynamics, Boltzmann transport theory
* **Software:** Gaussian, VASP, Quantum ESPRESSO, BoltzTraP2
* **Programming:** Python (NumPy, SciPy, Matplotlib, TensorFlow), Jupyter Notebooks, shell scripting (HPC)

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Talks

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
