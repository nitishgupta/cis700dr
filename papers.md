---
layout: default
title: Papers
active_tab: papers
---

<!-- ### <font color="blue">Introduction</font> (Lecture [1](slides/Lec1-Intro-2017.pptx)) -->

### Suggested Reading
<br>
### Some Relevant Classical papers on Knowledge Representation and Reasoning
{% for paper in site.data.papers.old %}
{% if paper.link %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% else %}
* {{ paper.authors}} {{ paper.title }}
{% endif %}
{% endfor %}
<br>

### Survey Paper
{% for paper in site.data.papers.survey %}
{% if paper.link %}
* {{ paper.authors}} [{{ paper.title }}]({{ paper.link }}) {{ paper.venue}}
{% else %}
* {{ paper.authors}} {{ paper.title }}
{% endif %}
{% endfor %}

<br>

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
