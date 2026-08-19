---
permalink: /CV/
title: "CV"
# excerpt: "Electronic CV stored here."
excerpt: "I’m interested in understanding physical processes in polar regions with global significance for humans and climate, such as the mechanisms and consequences of ice mass loss. Thanks for stopping by!"
header:
  overlay_image: /assets/images/niall-photo.jpg
  overlay_filter: 0.0  # Darkens the image (0.0 = no darkening, 1.0 = completely black)
  caption: "Ellwood Mesa, July 2024"
---

<style>
.page__hero--overlay {
  min-height: 450px !important;
  background-position: 70% 30% !important;
}
</style>

<!-- For a complete CV, please contact me at nbcoffey@stanford.edu. -->

<!-- ### Research Interests
I’m interested in understanding physical processes in polar regions with global significance for humans and climate, such as the mechanisms and consequences of ice mass loss.  -->
<!-- For more information, see [research page](research.md). -->

### Education
**2023--2026** Ph.D. in Geophysics, Stanford University, Advised by Ching-Yao Lai; *Thesis:* [On the Tensile Fracture of Glacial Ice](https://purl.stanford.edu/bg726cn0210)

**2021--2023** Ph.D. Student in Atmospheric and Oceanic Science, Princeton University, Transferred with advisor Ching-Yao Lai to Stanford

**2017--2021** B.A. in Physics (specialization Astrophysics) and Economics (specialization Data Science), University of Chicago

### Publications (\*: co-first authors)
#### In review
<ul style="list-style: none; padding-left: 0; margin-left: 0;">
  {% assign count = site.data.in_review | size %}
  {% for paper in site.data.in_review %}
    <li style="margin-bottom: 1.5em; text-indent: -2.5em; padding-left: 2.5em; list-style-type: none;">
      <strong>[{{ count }}]</strong> {{ paper.authors }} {{ paper.year }}. {{ paper.title }} <em>{{ paper.journal }}</em>, {{ paper.status }}.
      {% if paper.url %}
        <a href="{{ paper.url }}">{{ paper.doi_label }}</a>
      {% endif %}
    </li>
    {% assign count = count | minus: 1 %}
  {% endfor %}
</ul>

#### Published
<ul style="list-style: none; padding-left: 0; margin-left: 0;">
  {% assign count = site.data.papers | size %}
  {% for paper in site.data.papers %}
    <li style="margin-bottom: 1.5em; text-indent: -2.5em; padding-left: 2.5em; list-style-type: none;">
      <strong>[{{ count }}]</strong> {{ paper.authors }} {{ paper.year }}. {{ paper.title }} <em>{{ paper.journal }}</em>, {{ paper.pages }}. <a href="{{ paper.url }}">{{ paper.doi_label }}</a>
    </li>
    {% assign count = count | minus: 1 %}
  {% endfor %}
</ul>

### Data Sets
<ul style="list-style: none; padding-left: 0; margin-left: 0;">
  {% assign count = site.data.datasets | size %}
  {% for data in site.data.datasets %}
    <li style="margin-bottom: 1.5em; text-indent: -2.5em; padding-left: 2.5em; list-style-type: none;">
      <strong>[{{ count }}]</strong> {{ data.authors }} {{ data.year }}. {{ data.title }} <a href="{{ data.url }}">{{ data.doi_label }}</a>
    </li>
    {% assign count = count | minus: 1 %}
  {% endfor %}
</ul>

### Presentations
See [presentations page](presentations.md).

### Honors
  * **2025** AMS Denver Summit Poster Honorable Mention
  * **2024** CalGFD Best Poster
  * **2021-2023** President's Fellowship
  * **2020** College Research Fellow, Micro-Metcalf Intern, Metcalf Intern
  * **2019** Marine Biological Laboratory Scholarship, Enrico Fermi Institute Undergraduate Research Scholarship 
  * **2018** Metcalf Intern
  * **2017--2019** Dean's List

### Teaching
#### Guest Lecturer
  * ESS 246B Atmosphere, Ocean, and Climate Dynamics: The Ocean Circulation, Stanford University, February 2026
  * GEOPHYS 248 Machine Learning and the Physical Sciences, Stanford University, April 2024 – June 2024

#### Teaching Assistant
  * GEOPHYS 248 Machine Learning and the Physical Sciences, Stanford University, April 2024 – June 2024
  * AOS 551 Deep Learning in Geophysical Fluid Dynamics, Princeton University, September 2022 - December 2022

#### Technical Teaching Assistant: COMSOL
  * GEOS 34230 Geophysical Fluid Dynamics: Foundations, University of Chicago, September 2020 - December 2020

#### Youth Education
  * Office of Special Programs - College Prep (Math), Chicago, Illinois, November 2017 - June 2018
  * Neighborhood Schools Program - Carnegie Elementary School (First Grade Reading), Chicago, Illinois, January 2018 - June 2018

### Volunteering	
#### Peer Review
  * Journal of Glaciology, March 2025 - Present
  * The Cryosphere, November 2024 - Present

#### Conference Organization & Planning
  * 6th Annual California Geophysical Fluid Dynamics Conference, Stanford, CA, June 2024 – September 2024
