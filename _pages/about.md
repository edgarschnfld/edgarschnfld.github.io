---
layout: about
title: About
permalink: /
subtitle: <a href='https://scholar.google.com/citations?user=tvgSaXsAAAAJ&hl=en&oi=ao'>Scholar</a> | <a href='https://github.com/edgarschnfld'>GitHub</a> | <a href='https://www.linkedin.com/in/edgar-schoenfeld-4b259412b/'>LinkedIn</a> | <a href='https://twitter.com/schoenfeldedgar'>Twitter</a> | <a href='mailto:edgarschoenfeld@live.de'>Email</a>


profile:
  align: right
  image: prof_pic_square.jpg
  address: >
#    <p>555 your office number</p>
#    <p>123 your address street</p>
#    <p>Your City, State 12345</p>

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
years: [2021,2020,2019]
---

I am a PhD student in Machine Learning and Computer Vision at the [Bosch Center for AI](https://www.bosch-ai.com/) and Saarland University in Germany, advised by [Anna Khoreva](https://www.bosch-ai.com/research/researcher-pages/t_overviewpage_47.html) and [Bernt Schiele](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/people/bernt-schiele). Previously, I graduated with a Master's degree in Artificial Intelligence from the University of Amsterdam and a Bachelor's degree in Nanobiology from Delft Technical University.

While main research interest is controllable image synthesis, I am also very curious about out-of-distribution generalization, zero-shot generalization, compositionality and causality.


<br />
{: #publications}
## __Publications__
<!-- _pages/publications.md -->
<div class="publications">
  {% for y in page.years %}
    {% bibliography -f papers -q @*[year={{y}}]* %}
  {% endfor %}
</div>
