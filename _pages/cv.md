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
* Ph.D. in Earth Sciences, The Ohio State University, 2026 (expected)
* M.S. in Earth Sciences, The Ohio State University, 2022
* B.A. in Chemistry, Berea College, 2020

Professional Appointments
======
* Fall 2021 - present: Graduate Research Associate
  * Byrd Polar and Climate Research Center, The Ohio State University
  * Responsibilities: Conduct research relating to ice core paleoclimatology; communicate findings through conference presentations and peer-review publications; develop software for data visualization and quantitative analysis; field work at the Quelccaya Ice Cap (Peru)
  * Supervisor: [Lonnie G. Thompson](https://byrd.osu.edu/people/thompson.3), Ph.D.

* Summer 2019: Natural History Research Experience Intern
  * Smithsonian Institution, Washington, DC
  * Responsibilities: Conduct mineralogical research on the magmatic thermal histories of granites; utilize microanalytical techniques such as EPMA, SEM-EDS, and micro-CT; field work in the Mt. Princeton batholith and San Juan volcanic field (southwestern Colorado)
  * Supervisor: [Michael R. Ackerson](https://profiles.si.edu/display/nAckersonM1172018), Ph.D.
  
Skills
======
* Programming (MATLAB, Python, Julia, C++)
* Ice core paleoclimatology
* Machine Learning
* Geospatial analysis (QGIS, Google Earth Engine)
* Image Processing
* Analytical chemistry
* Technical writing and communication (Word, LaTeX, Markdown)

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

Awards and Honors
======
**2025** - Friends of Orton Hall Ph.D. Research Grant for Ice Core Mineral Dust Analysis ($4,159) 

**2025** - Wiley Top Viewed Article Recognition for article ranked within the top 10% of most-viewed papers published in 2023. 

**2024** - Michael Johnson Graduate Student Award – Outstanding PhD Candidate Starting Research 

**2023** - Distinguised Graduate Teaching Award for Excellence in Classroom Teaching, School of Earth Sciences

**2023** - School of Earth Sciences Orton Distinguished Service Award for Excellence in Research and Outreach  

**2022** - School of Earth Sciences Orton Distinguished Service Award for Excellence in Research and Outreach 

**2021** - Friends of Orton Hall Research Grant for Electron Microscopy ($4,060) 

**2020** - University Fellowship, Awarded by the Graduate School at The Ohio State University 

**2020** - Berea College Chemistry Department Class of 1958 Research Excellence Award

**2019** - Natural History Research Experience (NHRE) Internship, Smithsonian Institution, Washington, DC

**2019** - KBRIN Summer Research at the University of Louisville (accepted NHRE offer instead)

**2019** - 1st Place Poster Presentation in Geology, Kentucky Academy of Sciences Annual Meeting

**2019** - 3rd Place Men's Javelin, NCAA Division III USA South Conference Championships

**2016** - Berea College No Tuition-Promise Scholarship ($120,000)

**2015** - Cincinnati Mercantile Library Timothy Crane Day Award for Creative Writing
  
Service and leadership
======
* Guided 30+ public and private tours of the Byrd Polar and Climate Research Center since 2021.
* Served as a member of The Ohio State University Interdisciplinary Water Research Symposium Planning Committee since 2024.
* Led six C-ROADS mock U.N. climate simulations at various universities and other institutions since 2021.
* Participated in numerous [NSF Polar Literacy](https://polar-ice.org/) and [Arctic Mystery](https://par.nsf.gov/servlets/purl/10411605) outreach events.
* Led a field work-inspired survival game at "Climate Chronicles: An Interactive Exhibit" at the Ohio Union.
* Assisted with the Byrd Polar and Climate Research Center Outreach Booth at the 2023 Ohio State Fair.
* Volunteer at the 2024 Central Ohio Mineral, Fossil, Gem, and Jewelry Show.

Software
======
**2026** - **StokesSimulator**. GUI application for simulating the settling velocities of particles in the atmosphere using a Stokes' Law approximation. Dynamically adjust parameters such as elevation, mineralogy, and aspect ratio to visualize how gravitational settling changes under different scenarios. [https://github.com/weber1158/StokesSimulator](https://github.com/weber1158/StokesSimulator)

**2025** - **SNICARv3** [Contributor]. The Snow, Ice, and Aerosol Radiative model (SNICAR). Developed a graphical user interface (GUI) and functions to help users run the model locally in the MATLAB environment. [https://github.com/mflanner/SNICARv3](https://github.com/mflanner/SNICARv3)

**2025** - **EDS Classification**. MATLAB and Julia algorithms for identifying minerals in SEM-EDS data. The repository also includes functions for reading and visualizng x-ray spectral data and extracting metadata from SEM images. [https://github.com/weber1158/eds-classification](https://github.com/weber1158/eds-classification)

**2025** - **netIntensity.py**. A "Jython" script (Python2 implemented in Java) for evaluating the net intensities of common mineral-forming elements from EDS spectra in the NIST software DTSA-II. [https://github.com/weber1158/netIntensity.py](https://github.com/weber1158/netIntensity.py)

**2025** - **Colordle**. A color guessing game inspired by the New York Times game Wordle. [https://github.com/weber1158/colordle](https://github.com/weber1158/colordle)

**2025** - **cd2**. A MATLAB function for changing the current folder. Calling `cd2()` opens a dropdown menu for users to choose from a list of favorite folders instead of requiring the user to manually input the full name of the folder path. [https://github.com/weber1158/cd2](https://github.com/weber1158/cd2)

**2025** - **PDS**. A graphical user interface (GUI) for working with the NCEI Paleo Data Search API in MATLAB. [https://github.com/weber1158/pds](https://github.com/weber1158/pds)

**2024** - **Core Stratigraphy Visualization**. Repository of functions for making beautiful representations of ice, sediment, and rock cores. [https://github.com/weber1158/core-plot](https://github.com/weber1158/core-plot)

**2024** - **MATLAB Particle Size Functions**. Repository of particle size functions written in MATLAB for evaluating log-normalized particle concentrations, converting particle diameter sizes from metric units to the phi "φ" scale (and vice-versa), and classifying particle sizes according to the Wentworth Scale. [https://github.com/weber1158/MATLAB-particle-size-functions](https://github.com/weber1158/MATLAB-particle-size-functions)

**2024** - **Dracula**. Implementation of the popular Dracula dark theme in MATLAB, specifically for converting figures into the Dracula theme. [https://github.com/weber1158/dracula](https://github.com/weber1158/dracula)

**2024** - **groupedSpacedBoxchart**. A modified version of the MATLAB function `boxchart` that allows the user to create grouped box charts with added spacing between the groups. [https://www.mathworks.com/matlabcentral/fileexchange/166461](https://www.mathworks.com/matlabcentral/fileexchange/166461)

**2024** - **radialhistogram**. A function for visualizing categorical data in polar coordinates in MATLAB. [https://www.mathworks.com/matlabcentral/fileexchange/157796](https://www.mathworks.com/matlabcentral/fileexchange/157796)

**2023** - **ByrdDIT**. The Byrd Data Import Tool: an easy-to-use MATLAB app designed for quickly downloading datasets published by the Byrd Polar and Climate Research Center's ice core paleoclimatology group. [https://github.com/weber1158/ByrdDIT](https://github.com/weber1158/ByrdDIT)

Theses and Dissertations
======
2. **Weber, A. M.** "Mineral Dust in the Huascarán Ice Cores" (in progress). [Ph.D. Dissertation]. The Ohio State University.
1. **Weber, A. M.** "Amazonian influences on the hydrological and mineralogical signals preserved in an ice core from the Cordillera Blanca, Peru" (2022). [M.S. Thesis]. The Ohio State University.

Field Work
======
**2023 - Quelccaya Ice Cap, Peru** (5676 m a.s.l.). Objectives included (i) the collection of recently exposed plant material along the margins of the ice cap for carbon dating, (ii) drilling firn cores from the Quelccaya summit, and (iii) collecting snow surface samples for microbial, DNA, and RNA analyses. Byrd Polar and Climate Research Center.

**2019 - Rocky Mountains, Colorado, USA** (~4000 m a.s.l.). Rock sampling from the Mt. Princeton batholith (granodiorite) and the San Juan volcanic field (Fish Canyon tuff). Department of Mineral Science, Smithsonian Institution.

Selected Coursework
======
*Graduate*

Advanced Oceanography · Ecohydrology · Elemental Chemical Analysis using ICP-Optical Emission and Mass Spectrometry · Geomorphology · Glaciology · Intro to Geochemistry · Machine Learning and Artificial Intelligence in Earth Sciences · Paleoclimatology · Scanning Electron Microscopy · Seminar in Glaciology and Geomorphology · Seminar in Hyrdoclimatology · Seminar in Stratigraphy (Field course; Guadalupe Mtns., TX) · Stratigraphy and Sedimentation · Weather, Climate, and Global Warming

*Undergraduate*

Advanced Chromatography · Advanced Spectroscopy · Advanced Nuclear Magnetic Resonance (NMR) Spectroscopy · Advanced Organic Synthesis · Analytical Chemistry · Biochemistry I & II · Calculus I & II · Cell & Molecular Biology · Inorganic Chemistry · Mineralogy · Organic Chemistry I & II · Physics I & II

Languages
======
* English (native speaker)
* Mandarin Chinese (Duolingo, 100% course completion 2020-2022)
