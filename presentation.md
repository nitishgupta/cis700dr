---
layout: default
title: Paper Presentation
active_tab: presentation
---


<table class="table table-striped">
  <tbody>
    <tr>
      <th>Date</th>
      <th>Paper</th>
      <th>Presenter</th>
    </tr>
    {% for paper in site.data.papers.suggested %}
    <tr>
      {% unless paper.nopresent %}
          <td>{{ paper.date | date:  "%b %d, %y" }}</td>
          <td><a href="{{ paper.link }}">{{ paper.title }}</a></td>
          <td>{{ paper.presenters }}</td>
      {% endunless %}
    </tr>
    {% endfor %}
</tbody>
</table>
