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
* PhD, Institute of Language, Cognition, and Computation, School of Informatics, University of Edinburgh, 2023 (expected)
* MSc in Computational Linguistics, University of Washington, 2018
* BA in Linguistics, Brigham Young University, 2015



Work experience
======
* 2018-2019: Machine learning engineer, Bose Corporation
  * Developed solutions to problems in speech and language processing in order to drive product development

* 2017: Computational linguist, contractor through Appen Inc., onsite at Facebook Inc.
  * Develop data curation practices and standards for several diverse NLU projects.
  

Publications
======
  <ul>
    {% assign sorted = site.publications | reverse %}
    {% for post in sorted %}
     {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% assign sorted = site.teaching | reverse %}
  {% for post in sorted %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Python
* Machine learning, including deep learning (using PyTorch)

Languages
======
* English (native)
* Russian (fluent (C2))
* Spanish (conversational)
* French (read)
