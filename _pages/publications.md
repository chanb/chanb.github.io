---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[1] O. Limoyo, B. Chan, F. Maric, B. Wagstaff, A. R. Mahmood and J. Kelly, "Heteroscedastic Uncertainty for Robust Generative Latent Dynamics," in IEEE Robotics and Automation Letters, doi: 10.1109/LRA.2020.3015449.  
[ArXiv](https://arxiv.org/abs/2008.08157) | [Code](https://github.com/utiasSTARS/robust-latent-srl) | [Presentation](https://www.youtube.com/watch?v=tPLUqhobVzw&ab_channel=UTIASSTARSLab)  
![heteroscedastic_uncertainty]({{ base_path }}/images/heteroscedastic_uncertainty.svg)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
