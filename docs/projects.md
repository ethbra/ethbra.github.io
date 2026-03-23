---
layout: page
title: Projects
permalink: /projects/
---

This is a page demonstrating my work with various modern technologies

{% for project in site.projects %}
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
  <p>{{ project.description }}</p>
{% endfor %}
