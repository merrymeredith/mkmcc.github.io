---
title: Publications
layout: page
---

Publications
------------

<ol reversed="true">
{% for paper in site.data.papers %}
  <li markdown="span">
    [{{ paper.authors }} ({{paper.year }})]({{paper.url}})
  </li>
{% endfor %}
</ol>



Talks
-----

<ol reversed="true">
{% for talk in site.data.talks %}
  <li markdown="span">
    *{{ talk.name }}*, {{talk.place }} ({{ talk.date }})
  </li>  
{% endfor %}
</ol>
