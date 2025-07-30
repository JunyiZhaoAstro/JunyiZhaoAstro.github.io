---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Welcome to My Research Website! 

During my undergraduate studies, I worked on a diverse set of research projects—from searching for giant, mysterious emission-line stars to recovering debris-disk parameters with joint modeling though multiple wavelengths. I’ve handled data from facilities including [JWST/NIRCam](https://jwst-docs.stsci.edu/jwst-near-infrared-camera#gsc.tab=0), [ALMA](https://www.almaobservatory.org/en/home/), the [CHARA Array](https://www.chara.gsu.edu/public/tour-overview), [and CTIO’s Curtis/Schmidt Telescope](https://noirlab.edu/public/programs/ctio/curtis-schmidt-telescope/).

The discovery and characterization of alien worlds have always captivated me: from the structure of gas in protoplanetary disks, to the atmospheric composition of super-Earths, to detecting exoplanets from their faintest signals. I’m eager to explore entire exosystems across the full electromagnetic spectrum, seeking to understand how multiple components within the alien worlds (host star, gas, planets and their atmospheres) interact and shape each other. To me, probing these distant worlds is not only an exhilarating scientific journey but also a way to understand our place in the cosmos and tackle the biggest questions: Are we alone? How did planetary systems like our own assemble and evolve?

Below are the details of my research projects, if you are interested, please don't hesitate to email me at **junyzhao@umich.edu**.  I would love to chat!

<p>&nbsp;</p>
<p>&nbsp;</p>

# Constraining Grain-Size-Dependent Dynamics in AU Mic’s Debris Disk
## Advisor: [Dr.Yinuo Han](https://yinuohan.github.io/)
## 06/2025 - Now

Project under development

<p>&nbsp;</p>

# **Identification and Kinematics of OBe stars in the LMC**
## Advisor: [Prof.Sally Oey](https://sites.lsa.umich.edu/msoey/)
## 02/2023 - 05/2024


In our research, we tested the traditional approach of identifying OBe star candidates by using Hα-continuum subtracted images. Specifically, we compared the candidates detected through this method in the Large Magellanic Cloud (LMC) with known OBe stars listed in an established catalog. To do this, we extracted star-shaped objects from the Hα-continuum subtracted images and then evaluated how this group matched up with the cataloged OBe stars in the same region of the LMC. we find that this method results in false positives and is thus insufficient in identifying OBe stars.
We also measure the proper motions of OBe stars within the LMC using data from Gaia DR3. We then combine these findings with the proper motion characteristics of OBe stars in the Small Magellanic Cloud (SMC) region. We find that the velocity distributions of OBe stars in the LMC and the SMC are very similar. However, the velocity of OBe stars in the LMC is slightly higher than in the SMC. 

### How to find OBe stars
![BSS_HR](https://junyizhaoastro.github.io//images/OBe_star.png){: style="width: 50%; max-width: 550px; height: auto; float: right;"}
The conventional method of identifying OBe stars results in a high number of false positives because OBe stars are not the only objects that appear on a cont-sub Hα image. Other celestial bodies, such as planetary nebulae and red giants, also appear on these images, leading to misidentification. To address this issue, we analyzed the objects across different spectral bands and discovered that OBe stars typically exhibit a bluer g-r index compared to other objects, as indicated in Fig on the right

<div style="clear: both;"></div>

### The velocity distribution of OBe stars
![BSS_HR](https://junyizhaoastro.github.io//images/OBe_star_speed.png){: style="width: 50%; max-width: 550px; height: auto; float: right;"}
The velocity of OBe stars is a critical area of study since it can reveal probe cluster dynamical evolution, binary population parameters, and stellar evolution. We obtained the velocities of the OBe stars from the Reid & Parker catalog using the Gaia DR3 data. The field transverse velocity of the OBe stars is obtained through the median of the velocity of the stars within a 3-arcsec radius of the OBe stars. We discovered that the velocity distributions of OBe stars in LMC and SMC are very similar. However, the velocity of OBe stars in the LMC is slightly higher than in the SMC. 

<div style="clear: both;"></div>


<p>&nbsp;</p>



# Searching for protoplanets orbiting MWC 758 using JWST/NIRCam
## Advisor: [Prof.Michael Meyer](https://sites.lsa.umich.edu/feps/)
## 05/2024 - 08/2024

MWC 758 is a Herbig Ae star surrounded by a protoplanetary disk with a proposed attenuation protoplanet candidate, MWC 758c. We conducted high-contrast imaging observations with JWST/NIRCam in the F200W band, applying four PSF-subtraction techniques: PCA-based angular differential imaging (ADI), PCA with reference angles, roll-subtraction, and reference differential imaging (RDI). None of these methods revealed a companion at the predicted 0.62″ separation. The PCA-ADI contrast curve (PCA = 2) achieves a planet-to-star flux ratio sensitivity of ≲10⁻⁵ at that separation, placing stringent non-detection limits on MWC 758c. 

### Direct imaging results
![BSS_HR](https://junyizhaoastro.github.io//images/F200W_direct.png){: style="width: 50%; max-width: 550px; height: auto; float: right;"}
We use JWST/NIRCam filter F200W (centers at 2 microns) and run 4 different methods of PSF subtraction. Principal component analysis (PCA) analyzes the stack of stellar PSFs to pull out their common patterns, builds a PSF“template” from those patterns, and subtracts it so that only non‑stellar signals (like a rotating planet) remain. We can observe the disk structure of the system in the RDI subtraction method. For the results, **We do not detect MWC758c from the JWST/NIRCam F200 band** 

Future work includes calculating contrast for the other methods and analyzing data from the F430 filter. 



<div style="clear: both;"></div>


<p>&nbsp;</p>





  




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



