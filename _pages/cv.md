---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.archive .cv-research {
  font-size: 16px;
  line-height: 1.6;
}
.archive .cv-research h2 { font-size: 1.5em; }
.archive .cv-research h3 { font-size: 1.125em; margin-top: 1.75em; }
.archive .cv-research h4 { font-size: 1em; margin-top: 1.25em; }
.archive .cv-research li { margin-bottom: 0.5em; }
</style>

<div class="cv-research" markdown="1">

## Research experience

### Research Fellow — Thomas Jefferson University, Philadelphia, PA (Remote)

**Aug 2018–Present**  
Integrated MRI Center · Department of Neurosurgery  
Advisor: Chengyuan Wu, MD, MSBmE; Mahdi Alizadeh, PhD

* Investigate brain network organization and neuromodulation across epilepsy, Parkinson’s disease, chronic pain, and related neurological conditions using resting-state fMRI, MRI, DTI, and CT.
* Develop study-specific computational methods, including automated localization and quantitative comparison of implanted versus planned DBS trajectories in 3D Slicer and MATLAB-based visualization of DBS ON/OFF BOLD signal changes.
* Perform quantitative neuroimaging analyses including image preprocessing, ICA, ROI-based functional connectivity, dynamic functional connectivity, tractography, and group-level statistical analysis.
* Lead and contribute to study design, imaging preprocessing and analysis, interpretation and visualization of findings, literature synthesis, manuscript development, and training of junior researchers.
* Coordinate multidisciplinary studies integrating imaging, clinical, and demographic data in collaboration with neurosurgeons and neuroimaging researchers.
* Research resulted in 13 peer-reviewed publications, a book chapter, and multiple abstracts presented at national scientific meetings.

### Research Assistant — Santa Clara Valley Medical Center, Santa Clara, CA

**Jan 2022–Aug 2022**  
Department of Neurosurgery  
Advisor: Harminder Singh, MD

* Conducted retrospective clinical and CT imaging analyses of traumatic brain injury and thoracolumbar trauma, contributing to demographic analysis, IRB documentation, and multidisciplinary neurosurgical research.
* Research contributed to three peer-reviewed publications on neurosurgical and trauma outcomes.

### Research Assistant — Thomas Jefferson University, Philadelphia, PA

#### Department of Neurosurgery

**Aug 2021–Jun 2023**  
Advisor: James Harrop, MD

* Conducted EMR-based clinical research on spine disorders and neurosurgical outcomes, including clinical data collection, literature review, and interpretation of findings.
* Contributed to manuscript development, particularly introduction and discussion sections; research resulted in 7 peer-reviewed journal articles.

#### Department of Radiology

**Aug 2020–Jun 2021**  
Advisor: John Eisenbrey, PhD

* Collected patient clinical data from EMR/Epic for exploring the contributing factors in the incidences of LI-RADS equivocal diagnosis after locoregional therapies of hepatocellular carcinoma.
* Developed a clinical research protocol for assessing the correlations between hypoxia and the development of post-radiation fibrosis in patients treated for head and neck cancer.

#### Molecular Biology Research in Orthopedics

**Aug 2018–Jun 2019**  
Advisor: Makarand Risbud, PhD

* Investigated cellular senescence and intervertebral disc degeneration in mouse models using histological and molecular techniques (IHC, IF, Western blotting, ELISA, PCR, and flow cytometry) and quantitative image analysis; resulting publication: Aging Cell (2020).

### Undergraduate Research Assistant & M.S. Thesis — Drexel University, Philadelphia, PA

Biomedical Engineering, Neural Biomechanics | Jan 2013–Mar 2016  
Advisor: Kenneth Barbee, PhD

* Investigated neural-cell responses to traumatic mechanical loading using cultured frontal-lobe cells, microscopy, and quantitative image analysis.
* For M.S. thesis, designed and evaluated an improved in vitro cell-shearing device to deliver precisely controlled high-shear-stress impulses to neural cells.

### Undergrad Research Assistant — Lankenau Institute for Medical Research

**Sep 2012–Mar 2013**  
Molecular and Cell Biology in Gastroenterology  
Advisor: Dr. James Mullin

* Investigated micronutrient effects on epithelial barrier function using electrical cell-layer models and quantitative analysis; research resulted in a peer-reviewed publication in PLOS ONE (2013).

</div>

{% comment %}
Original CV content preserved below, including its Markdown formatting and Liquid includes.
To restore a section, move it outside this comment block.


{% include base_path %}

## Education

* Training in Osteopathic Medicine, Western University of Health Sciences
  * Completed preclinical curriculum and clinical clerkships, 2021 - 2025
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
  <!-- * DBS on-off (ongoing)
    * Developed MATLAB script to visualize brain BOLD signal changes as DBS turned on vs. off to understand impacts of DBS on Parkinson disease. -->
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

{% endcomment %}
