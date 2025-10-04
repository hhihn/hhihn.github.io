---
layout: default
title: Research
---

## RESEARCH INTERESTS

My current research focuses on several key areas:

### Primary Research Areas

* **Area 1**: Detailed description of your first research area
* **Area 2**: Description of your second focus area
* **Area 3**: Third area of research specialization

### CURRENT PROJECTS

{% for post in site.posts %}
{% if post.categories contains "projects" %}
* [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.excerpt | strip_html | truncate: 100 }}
  {% endif %}
  {% endfor %}

### RESEARCH PHILOSOPHY

Write about your approach to research, methodology, and overall philosophy here.