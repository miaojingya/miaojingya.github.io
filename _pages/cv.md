---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* Training in Osteopathic Medicine, Western University of Health Sciences
  * Completed Preclinical curriculum and Clinical clerkships, 2021 - 2025
* M.S. in Biotechnology, Thomas Jefferson University, 2019
* B.S./M.S. in Biomedical Engineering, Drexel University, 2016

## Research experience

* **Neurosurgery/Neuromodulation Research** <br>
Research Fellow, Thomas Jefferson University Hospital |  Aug 2018-Present<br>
[Chengyuan Wu, MD, MSBmE](https://research.jefferson.edu/labs/researcher/wu-laboratory.html); Mahdi Alizadeh, PhD  
  * DBS Deviation Localization in Parkinson’s Disease (ongoing)
    * Developing automated localization of DBS electrodes for assessing electrode deviation due to physical obstacles of brain tissue, using python in 3D Slicer environment. 
    * Through quantitative and precise DBS localization compared to planned trajectory to improve reproducibility and clinical outcomes. 
    <!-- * GitHub repository: link -->
  *DBS on-off (ongoing)
    * Developed MATLAB script to visualize brain BOLD signal changes as DBS turned on vs. off to understand impacts of DBS on Parkinson disease.
  * Functional Connectivity in Spinal Cord Injury, Epilepsy, Anesthesia 
    * Investigated dynamic functional connectivity using resting state fMRI in temporal lobe epilepsy using ICA, seed/ROI-based analysis and group-level statistical approaches. 
    * Developed/implemented imaging workflows relating seizure network organization to LITT treatment outcomes
  * Tractography and visualization - resulted in a book chapter ([Functional Neuroradiology](https://doi.org/10.1007/978-3-031-10909-6_41)).
  * Systematic review – from idea initiation to final publication ([doi](https://doi.org/10.3389/fneur.2022.849918))
  

* **Molecular & Cellular Orthopedic Research** <br>
Research Assistant, Thomas Jefferson University | Aug 2018-Jun 2019<br>
[Makarand Risbud, PhD](https://research.jefferson.edu/labs/researcher/risbud-laboratory.html)
  * Investigated cellular senescence and intervertebral disc degeneration using mouse models, including spine dissection, histology and molecular biology techniques (IHC, IF, Western blotting, ELISA, PCR, and flow cytometry), and quantitative image analysis; resulting publication: [Aging Cell (2020)](https://doi.org/10.1111/acel.13148Digital)
  
## Skills

* **Neuroimaging Analysis:** preprocessing, functional connectivity (ICA/ROI-based, dynamic/static FC), and Tractography.
* **Neuroimaging Software:** FreeSurfer, FSL, MRtrix, SPM, CONN, 3D Slicer, TIK-SNAP, and DSI Studio.
* **Programming Languages:** MATLAB, Python, R, Unix/Linux shell script, and Git/GitHub
* **Laboratory Methods:** Histology, immunohistochemistry IHC), immunofluorescence (IF), Fluorescence microscopy, PCR, Western blotting, and ELISA.
* **Engineering:** Autodesk Fusion, SolidWorks, CAD, 3D printing


## Publications

  <ul class="cv-publications">
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  

## Service and Leadership
- Community Health Fair Volunteer, Wealth By Health Steps For Change Foundation — Rosemead, CA (2022–2024)
- Patient Navigator and Translator, Chinatown Clinic — Philadelphia, PA (2017–2021)
- Science Presenter Volunteer, The Franklin Institute — Philadelphia, PA (2016–2021)
- Peer Mentor, Thomas Jefferson University — Philadelphia, PA (2017–2019)
- Head of Public Relations, Alpha Eta Mu Beta, Drexel Chapter — Philadelphia, PA (2014–2015)

