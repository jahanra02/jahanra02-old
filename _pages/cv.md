---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my CV]({{ base_path }}/files/CV_Jahanara_Suchi_pdf.pdf)

Education
======
* B.S. in Computer Science and Engineering (CSE), American International University-Bangladesh (AIUB)

Research Interests
======
* Machine Learning
* Deep Learning
* Explainable Artificial Intelligence (XAI)
* Healthcare AI

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
