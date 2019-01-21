---
layout: default
title: Papers
active_tab: papers
---

<!-- ### <font color="blue">Introduction</font> (Lecture [1](slides/Lec1-Intro-2017.pptx)) -->

### Suggested Reading

Papers that are suggested for presenting are marked with **&#9829;**

<tbody>
    <ul>
        {% for paper in site.data.papers.suggested %}
    	   <li> {{ paper.authors}} <a href="{{ paper.link }}">{{ paper.title }}</a> {{ paper.venue}} </li>
        {% endfor %}
   </ul>
</tbody>

### Few old papers but good reads
<tbody>
    <ul>
        {% for paper in site.data.papers.old %}
    	   <li> {{ paper.authors}} <a href="{{ paper.link }}">{{ paper.title }}</a> {{ paper.venue}} </li>
        {% endfor %}
   </ul>
</tbody>
