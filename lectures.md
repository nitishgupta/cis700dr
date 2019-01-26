---
layout: default
title: Lectures
active_tab: lectures
---


<table class="table table-striped">
  <tbody>
    <tr>
      <th>Date</th>
      <th>Class</th>
      <!-- <th>Due</th> -->
      <th>Notes</th>
    </tr>
    {% for lecture in site.data.lectures %}
    <tr>
      <td>{{ lecture.date | date: "%b %d, %Y" }}</td>
      <td>
	{% if lecture.slides %}
	<a href="{{ lecture.slides }}">{{ lecture.title }}</a>
	{% else %}
	{{ lecture.title }}
	{% endif %}
      </td>
      <!-- <td>
	{% if lecture.due %}
	<b>{{ lecture.due }}</b>
	{% endif %}
      </td> -->
      <td>
	{% if lecture.reading %}
	  <b>Required Reading</b>
          <ul class="fa-ul">
          {% for reading in lecture.reading %}
            <li>
            {{ reading.author }},
            {% if reading.link %}
            <a href="{{ reading.link }}">{{ reading.title }}</a>
            {% else %}
            {{ reading.title }}
            {% endif %}
            </li>
          {% endfor %}
          </ul>
        {% endif %}
        {{lecture.comments}}
      </td>
    </tr>
    {% endfor %}
</tbody>
</table>
