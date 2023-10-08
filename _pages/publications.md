---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Neuro-Symbolic Language Modeling with Automaton-augmented Retrieval**  
Uri Alon, Frank F. Xu, *<ins>Junxian He</ins>*, Sudipta Sengupta, Dan Roth, Graham Neubig  
ICML 2022. [[arxiv]](https://arxiv.org/abs/2201.12431) [[code]](https://github.com/neulab/retomaton)
