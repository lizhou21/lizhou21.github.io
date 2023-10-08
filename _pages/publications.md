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

#2023
**Cultural Compass: Predicting Transfer Learning Success in Offensive Language Detection with Cultural Features**  
*<ins>Li Zhou</ins>*,  Antonia Karamolegkou, Wenyu Chen, Daniel Hershcovich
Findings of EMNLP 2023.

[comment]: <> ([[arxiv]]&#40;https://arxiv.org/abs/2201.12431&#41; [[code]]&#40;https://github.com/neulab/retomaton&#41;)

**Cultural Compass: Predicting Transfer Learning Success in Offensive Language Detection with Cultural Features**  
Antonia Karamolegkou, Jiaang Li, *<ins>Li Zhou</ins>*, Anders Søgaard
EMNLP 2023.

**Cross-Cultural Transfer Learning for Chinese Offensive Language Detection**
Li Zhou, Laura Cabello, Yong Cao, Daniel Hershcovich
Cross-Cultural Considerations in NLP Workshop at EACL 2023 [[Proceedings]](https://aclanthology.org/2023.c3nlp-1.2/) [[Arxiv]](https://arxiv.org/abs/2303.17927)

**Assessing Cross-Cultural Alignment between ChatGPT and Human Societies: An Empirical Study**
Yong Cao, *<ins>Li Zhou</ins>*, Seolhwa Lee, Laura Cabello Piqueras, Min Chen, Daniel Hershcovich
Cross-Cultural Considerations in NLP Workshop at EACL 2023 [[Proceedings]](https://aclanthology.org/2023.c3nlp-1.7/) [[Arxiv]](https://arxiv.org/abs/2303.17466)
