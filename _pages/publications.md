---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a complete list of my publications [here](https://kimiklein.github.io/list_publications.pdf).

Selected Publications
---
- [About the Complexity of Two-Stage Stochastic IPs](https://arxiv.org/abs/1901.01135) (2020)
- [An Algorithmic Theory of Integer Programming](https://arxiv.org/abs/1904.01361) (2019)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
