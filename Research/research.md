---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

My research spans **planetary science and astrophysics**, with a common emphasis on extracting physical information from complex observational data. I am particularly interested in combining remote sensing, image analysis, statistical inference, and numerical modeling to understand how planetary surfaces and circumstellar systems form and evolve.

My current work is centered on **lunar science**, while I remain actively involved in astrophysical research using facilities including **JWST** and **ALMA**.

---

# Current Research

## Lunar Impact Cratering and Surface Processes
**Advisor:** Dr. Yuqi Qian, The University of Hong Kong  
**2026 – Present**

<figure style="margin: 1rem 0 1.5rem;">
  <img src="/images/research-lunar-crater-topography.jpg" alt="Conceptual view of lunar south-polar crater morphology with a topographic analysis overlay" style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="font-size: 0.85em; color: #6f777d; margin-top: 0.35rem;">Conceptual illustration of lunar south-polar crater morphology and topographic analysis; not observational data.</figcaption>
</figure>

My Ph.D. research focuses on the geology and physical evolution of the Moon, with particular interest in **impact cratering, lunar polar environments, surface morphology, and quantitative planetary geomorphology**.

My first project is being developed around the **Chang’e-7 candidate landing region near the lunar south pole**. I am interested in using crater morphology and topography to extract quantitative information about surface evolution and local geologic processes, rather than treating crater shape only as a descriptive geologic feature. A major goal is to connect remote-sensing observations with **numerical calculations and impact-process modeling**, allowing observed morphology to be interpreted in a more physical framework.

More broadly, I am interested in questions such as:

- How do impact craters record the physical properties and modification history of the lunar surface?
- How can crater morphology and morphometry be used to characterize poorly illuminated polar terrain?
- What can topography, illumination, thermal environment, and remote-sensing data jointly tell us about lunar polar geology?
- How can numerical modeling be used to move from morphological description toward physically testable interpretations?

This work is currently under development as I begin my Ph.D. at HKU.

---

## Grain-Size-Dependent Structure of the AU Microscopii Debris Disk
**Advisor:** [Dr. Yinuo Han](https://yinuohan.github.io/)  
**2025 – Present**

<figure style="margin: 1rem 0 1.5rem;">
  <img src="/images/research-au-mic-multiwavelength.jpg" alt="Conceptual edge-on view of the AU Microscopii debris disk combining scattered-light and millimeter-grain structure" style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="font-size: 0.85em; color: #6f777d; margin-top: 0.35rem;">Conceptual illustration of joint JWST and ALMA modeling of the AU Microscopii debris disk; not observational data.</figcaption>
</figure>

Debris disks provide a direct view of the small-body populations left behind after planet formation. Because grains of different sizes respond differently to radiation, stellar winds, collisions, and gravity, comparing the same disk at different wavelengths provides a way to probe the underlying disk dynamics.

For the nearby AU Microscopii debris disk, I am leading a **joint multi-wavelength modeling analysis using JWST/NIRCam F444W scattered-light imaging and ALMA Band 6 interferometric observations**. The central goal is to test whether the vertical and radial structure traced by micron-sized grains differs from that traced by millimeter-sized grains.

Rather than fitting the two datasets independently, I developed a framework that models them jointly while sharing the disk geometry. The analysis combines an **image-plane likelihood for JWST** with a **visibility-space likelihood for ALMA**, and uses Bayesian sampling to constrain disk inclination, position angle, scale height, radial structure, scattering properties, and millimeter emission simultaneously.

This project has involved:

- Forward modeling of edge-on debris-disk structure
- JWST/NIRCam scattered-light image modeling
- ALMA interferometric visibility modeling in the \(u\)-\(v\) plane
- Bayesian parameter inference and MCMC
- Statistical model comparison
- Physical interpretation of wavelength-dependent disk structure

The broader aim is to understand how grain-size-dependent forces shape debris disks and how those processes differ between low-mass active stars such as AU Mic and more luminous systems.

---

# Previous Astrophysics Research

## Searching for Protoplanets around MWC 758 with JWST/NIRCam
**Advisor:** [Prof. Michael Meyer](https://sites.lsa.umich.edu/feps/)  
**University of Michigan · 2024**

<figure style="margin: 1rem 0 1.5rem;">
  <img src="/images/research-mwc-758-high-contrast.jpg" alt="Conceptual high-contrast view of the structured MWC 758 disk behind a coronagraphic mask" style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="font-size: 0.85em; color: #6f777d; margin-top: 0.35rem;">Conceptual illustration of high-contrast imaging of MWC 758 and a companion search; not observational data.</figcaption>
</figure>

MWC 758 is a young Herbig Ae star surrounded by a highly structured protoplanetary disk and has been proposed to host an embedded protoplanet, MWC 758c. I analyzed **JWST/NIRCam F200W high-contrast imaging** to search for the candidate companion and to characterize the sensitivity of the observations.

I implemented and compared several PSF-subtraction strategies, including PCA-based angular differential imaging, PCA using reference orientations, roll subtraction, and reference differential imaging. We did **not detect MWC 758c** at its predicted separation in the F200W data. The analysis instead provided quantitative contrast limits on a potential companion and demonstrated the importance of PSF treatment when working close to bright, structured circumstellar disks.

![JWST/NIRCam MWC 758 analysis](/images/F200W_direct.png){: style="width: 52%; max-width: 600px; height: auto; float: right; margin-left: 24px;"}

This project introduced me to high-contrast imaging with JWST and motivated my continued interest in extracting faint physical signals from strongly structured backgrounds.

<div style="clear: both;"></div>

---

## Identification and Kinematics of OBe Stars in the Large Magellanic Cloud
**Advisor:** [Prof. Sally Oey](https://sites.lsa.umich.edu/msoey/)  
**University of Michigan · 2023 – 2024**

<figure style="margin: 1rem 0 1.5rem;">
  <img src="/images/research-obe-lmc-kinematics.jpg" alt="Conceptual survey view of OBe-star selection and proper-motion analysis in the Large Magellanic Cloud" style="width: 100%; height: auto; border-radius: 8px;">
  <figcaption style="font-size: 0.85em; color: #6f777d; margin-top: 0.35rem;">Conceptual illustration of OBe-star candidate selection and transverse-motion analysis in the Large Magellanic Cloud; not observational data.</figcaption>
</figure>

O- and B-type emission-line stars are important tracers of massive-star evolution, binarity, and stellar feedback. In this project, I investigated both their **photometric identification** and their **kinematics in the Large Magellanic Cloud (LMC)**.

We tested the conventional use of Hα continuum-subtracted imaging to identify OBe-star candidates and found that this approach alone produces substantial contamination from other emission-line and red stellar populations. By incorporating broadband photometry, we showed that color information can significantly improve candidate selection.

![OBe-star identification](/images/OBe_star.png){: style="width: 48%; max-width: 560px; height: auto; float: right; margin-left: 24px;"}

I also used **Gaia DR3 proper motions** to examine the transverse-velocity distribution of cataloged OBe stars in the LMC and compare it with the corresponding population in the Small Magellanic Cloud. This part of the project introduced me to large-catalog analysis, astrometric data, and the use of stellar kinematics as a probe of massive-star evolution.

<div style="clear: both;"></div>

---

# Methods & Tools

Across these projects, I have worked with a range of observational and computational techniques. My current methodological interests include:

- **Planetary remote sensing and quantitative geomorphology**
- **Crater morphology, morphometry, and topographic analysis**
- **Numerical modeling of planetary surface processes**
- **JWST/NIRCam image analysis and high-contrast imaging**
- **ALMA interferometric visibility modeling**
- **Bayesian inference, MCMC, and statistical model comparison**
- **Forward modeling and image-plane / visibility-plane likelihoods**
- **Python-based scientific computing and astronomical data analysis**

I am especially interested in research where observational morphology can be translated into constraints on the underlying **physics** rather than treated only descriptively.
