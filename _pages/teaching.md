---
title: 'Teaching'
layout: splash
permalink: /teaching/
header:
  overlay_image: /images/splash.png
  text_color: black

aeesp:
  image_path: /images/teaching/aeesp.png
  alt: 'AEESP Workshop'
  title: 'QSD Workshop in AEESP Research and Education Conference'
  synopsis: 'During the 2022 [Association of Environmental Engineering and Science Professors (AEESP) Research and Education Conference](https://aeesp2022.wustl.edu), we hosted a workshop on Quantitative Sustainable Design (QSD). In this workshop, we familiarize participants with a structured approach to sustainable design (QSD) and provide experience in leveraging QSD to generate insight in their domains of interest.'
  image_width: 90%
  btn_num: 1
  btn_url1: 'https://uofi.box.com/s/o8vvpxzhydd3g7qw9i4zljzc13kygmd4'
  btn_class1: 'btn--primary btn--large'
  btn_label1: 'Workshop Materials'
  line: true

ees:
  image_path: /images/teaching/ees.png
  alt: 'EES Symposium Workshop'
  title: 'QSDsan Workshop in EES Symposium'
  synopsis: 'We hosted an entry-level workshop of QSDsan during the [27th Environmental Engineering and Science Symposium](https://publish.illinois.edu/2022-environmentalsymposium/) at the University of Illinois Urbana-Champaign. In this workshop, attendees could interact with QSDsan through [Binder](https://mybinder.org/) without any local installation and prior knowledge on programming.'
  image_width: 60%
  btn_num: 2
  btn_url1: 'https://github.com/QSD-Group/QSDsan-workshop'
  btn_class1: 'btn--primary btn--large'
  btn_label1: 'Workshop Materials'
  btn_url2: 'https://youtu.be/cO3LZpwOit8'
  btn_class2: 'btn--primary btn--large'
  btn_label2: 'Video Recording'
  line: true
---

## Course Instructed

### 16:180:562 Water and Wastewater Treatment

This course ([syllabus](https://drive.google.com/file/d/19XzQ_lioHbF59835jCJ6B5mjcsI5ftpH/view?usp=drive_link)) covers engineering processes commonly used for drinking water and wastewater treatment, as well as topics of emerging concern. Key topics include drinking water and wastewater quality criteria, water chemistry, integration of unit processes into full scale treatment facilities, reactor design, coagulation, flocculation, sedimentation, filtration, disinfection, water softening, microbiology and biological wastewater treatment, oxidation-reduction processes in treatment, nutrient removal, and residual solids management. A design module is also included that demonstrate the use of process simulation software.

<br>
<img src='/images/teaching/water_wastewater_treatment.png#center' alt='Water and Wastewater Treatment' width='60%' id='image'>

### 16:180:611 Sustainable Design

Through this course ([flyer](https://drive.google.com/file/d/1t_jPm0EzRcYOeHgUdtjyL_ZtY4LEXUyR/view?usp=sharing); [syllabus](https://drive.google.com/file/d/1X2lymRGmW4bngyPC34sctMACFFi6wT9n/view?usp=sharing)), students will develop an understanding of quantitative sustainable design (QSD) and how to navigate engineering decision-making. Students will learn methods and tools for economic (techno-economic analysis, TEA; life cycle costing, LCC) and environmental (life cycle assessment, LCA) sustainability assessments, and how to link these tools to engineering design decisions under uncertainty. Students will apply these tools to design their engineered systems of interest, with special attention to water and energy infrastructure, water quality processes, resource recovery, green chemistry, and bioenergy/bioproducts.

<br>
<img src='/images/teaching/sustainable_design.png#center' alt='Quantitative Sustainable Design' width='50%' id='image'>

---

## Workshop Modules

I see tremendous potentials in leveraging the open-source platforms developed in my research to build interactive modules to be used in the classroom. My goal is to make these experiences accessible to everyone - regardless of individuals' programing skills.

{% include single_left id='aeesp' %}

{% include single_right id='ees' %}


## New Jersey Bioenergy Potential

The New Jersey Agricultural Experiment Station (NJAES) conducted an assessment of NJ’s biomass and the potential for bioenergy production and published the results in the report titled *Assessment of Biomass Energy Potential in New Jersey*. The report was later updated by the Rutgers EcoComplex into the Bioenergy Calculator. Below you can find a quick visualization of the estimated gross biomass energy for 2010.

Refer to [Rutgers EcoComplex's website](https://ecocomplex.rutgers.edu/biomass-energy-potential.html) for the original report, the Bioenergy Calculator (including modeling assumptions and data sources).

This visualization module was developed with the help of [Yogesh Jaganathan](https://www.linkedin.com/in/yogesh-jaganathan-1970b4304/), a high-school senior from central jersey with a passion for technology and the environment.


<div id="main">
  <tableau-viz id="tableauViz" src="https://public.tableau.com/views/NJBioenergyPotential/Module"
    iframe-attr-loading="eager" iframe-attr-class="border">
    <iframe-style>
      .border { border: 1px solid #EFEFEF !important; }
      .fun { scale(1); }
    </iframe-style>

  </tableau-viz>
</div>
<script type="module">
  import { TableauEventType } from 'https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.min.js';
  const tableauViz = document.getElementById('tableauViz');
  window.addEventListener('resize', () => tableauViz.resize());
</script>

