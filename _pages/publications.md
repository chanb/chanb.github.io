---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[1] T. Ablett, __B. Chan__, and J. Kelly, "Learning from Guided Play: Improving Exploration in Adversarial Imitation Learning with Simple Auxiliary Tasks," in Robotics and Automation Letters (RA-L) 2022. 
<img src="/images/pubs/loopback-toy-example.png" width="800"/>  
<img src="/images/pubs/lfgp_all_tasks_plus_dac_v1_199999.png" width="800"/>  
[Paper](https://arxiv.org/abs/2301.00051) | [Code](https://github.com/utiasSTARS/lfgp) | [Website](https://papers.starslab.ca/lfgp/)

[2] T. Ablett\*, __B. Chan\*__, and J. Kelly, "Learning from Guided Play: A Scheduled Hierarchical Approach for Improving Exploration in Adversarial Imitation Learning," in Thirty-fifth Conference on Neural Information Processing Systems (NeurIPS),  Deep Reinforcement Learning Workshop. (\* equal contribution) 
<img src="/images/pubs/lfgp.svg" width="800"/>  
[Paper](https://arxiv.org/abs/2112.08932) | [Code](https://github.com/utiasSTARS/lfgp) | [Presentation](https://slideslive.com/38971121/learning-from-guided-play-a-scheduled-hierarchical-approach-for-improving-exploration-in-adversarial-imitation-learning) | [Website](https://papers.starslab.ca/lfgp/)

[3] O. Limoyo, **B. Chan**, F. Maric, B. Wagstaff, A. R. Mahmood and J. Kelly, "Heteroscedastic Uncertainty for Robust Generative Latent Dynamics," in Robotics and Automation Letters (RA-L) 2020 with IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS’20) Option, doi: 10.1109/LRA.2020.3015449.  
<img src="/images/pubs/heteroscedastic_uncertainty.svg" width="500"/>  
[Paper](https://arxiv.org/abs/2008.08157) | [Code](https://github.com/utiasSTARS/robust-latent-srl) | [Presentation](https://www.youtube.com/watch?v=tPLUqhobVzw&ab_channel=UTIASSTARSLab)  


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
