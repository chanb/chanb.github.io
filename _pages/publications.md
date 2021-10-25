---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[1] T. Ablett*, **B. Chan***, and J. Kelly, "Learning from Guided Play: A Scheduled Hierarchical Approach for Improving Exploration in Adversarial Imitation Learning," _(to appear)_ in Thirty-fifth Conference on Neural Information Processing Systems (NeurIPS),  Deep Reinforcement Learning Workshop.  
<img src="/images/pubs/lfgp.svg" width="500"/>  

[2] O. Limoyo, **B. Chan**, F. Maric, B. Wagstaff, A. R. Mahmood and J. Kelly, "Heteroscedastic Uncertainty for Robust Generative Latent Dynamics," in IEEE Robotics and Automation Letters, doi: 10.1109/LRA.2020.3015449.  
<img src="/images/pubs/heteroscedastic_uncertainty.svg" width="500"/>  
[arXiv](https://arxiv.org/abs/2008.08157) | [Code](https://github.com/utiasSTARS/robust-latent-srl) | [Presentation](https://www.youtube.com/watch?v=tPLUqhobVzw&ab_channel=UTIASSTARSLab)  


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
