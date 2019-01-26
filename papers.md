---
layout: default
title: Papers
active_tab: papers
---

<!-- ### <font color="blue">Introduction</font> (Lecture [1](slides/Lec1-Intro-2017.pptx)) -->

### Suggested Reading
<br>
 <!-- Papers that are suggested for presenting are marked with **&#9829;** -->
#### Information Extraction / Knowledge Acquisition
{% for paper in site.data.papers.suggested.ie_ka %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}
<br>
#### Reasoning
{% for paper in site.data.papers.suggested.reasoning %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}

<br>
#### Evaluation / Dataset
{% for paper in site.data.papers.suggested.evaluation_dataset %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}

<br>
#### Position papers
{% for paper in site.data.papers.suggested.position %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}

<br>
#### Informational websites
{% for paper in site.data.papers.suggested.info %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}

<br>
### Few old papers but good reads

{% for paper in site.data.papers.old %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% endfor %}
