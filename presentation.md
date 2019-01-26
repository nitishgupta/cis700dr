---
layout: default
title: Paper Presentation
active_tab: presentation
---

<!-- {% for papers in site.data.papers.suggested %}
{% for paper in papers[1] %}
{{paper.authors}}
{% endfor %}
{% endfor %} -->


<table class="table table-striped">
  <tbody>
    <tr>
      <th>Date</th>
      <th>Paper</th>
      <th>Presenter</th>
    </tr>
    {% for papers in site.data.papers.suggested %}
    {% for paper in papers[1] %}
    <tr>  
          {% unless paper.nopresent %}
              <td>{{ paper.date | date:  "%b %d, %y" }}</td>
              <td><a href="{{ paper.link }}">{{ paper.title }}</a></td>
              <td>{{ paper.presenters }}</td>
          {% endunless %}
    </tr>
    {% endfor %}
    {% endfor %}
</tbody>
</table>
