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
* Ph.D. candidate in Information Science, University of Michigan (expected)
* M.S. in Data Science, University of Michigan, 2023 (GPA: 3.9)
* B.S. in Computational and Applied Mathematics, Chinese University of Hong Kong, 2021

Work experience
======
* Fall 2025: Graduate Student Instructor
  * University of Michigan, School of Information
  * Course: SI 315 - Models of Social Information Processing
  * Duties include: Teaching, grading, and course development
  * Supervisor: Prof. [Sabina Tomkins](https://www.si.umich.edu/people/sabina-tomkins)
  
Skills
======
* **Programming Languages**: Python, R, SQL, JavaScript
* **Machine Learning**: Deep learning, NLP, computer vision, probabilistic modeling
* **Data Analysis**: Statistical analysis, network analysis, time series analysis
* **Tools & Frameworks**: PyTorch, scikit-learn, pandas, Jupyter
* **Languages**: Mandarin (Native), English (Fluent), Cantonese (Fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
News
======
  <ul>{% for post in site.news reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Submissions reviewer, IC2S2-25 (2025)
