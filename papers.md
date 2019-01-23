---
layout: default
title: Papers
active_tab: papers
---

<!-- ### <font color="blue">Introduction</font> (Lecture [1](slides/Lec1-Intro-2017.pptx)) -->

### Suggested Reading

 <!-- Papers that are suggested for presenting are marked with **&#9829;** -->

{% for paper in site.data.papers.suggested %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}


### Few old papers but good reads

{% for paper in site.data.papers.old %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}
