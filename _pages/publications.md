---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* Jiaxin Yuan, Amar Shah, Channing Bentz, and Maria Cameron. *Optimal control for sampling the transition path process and estimating rates.* 2023. submitted. arXiv: 2305.17112 [math.OC].
* Xiaoyu Liu, Jiaxin Yuan, Bang An, Yuancheng Xu, Yifan Yang, Furong Huang. *C-Disentanglement: Discovering Causally-Independent Generative Factors under an Inductive Bias of Confounder.* 1st SPIGM @ ICML Poster, 2023. accepted.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
