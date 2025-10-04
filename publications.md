---
layout: default
title: Publications
---

## PUBLICATIONS

### PEER-REVIEWED JOURNAL ARTICLES

{% for post in site.posts %}
{% if post.categories contains "publications" %}
1. [{{ post.title }}]({{ post.url | relative_url }})  
   *{{ post.authors }}*  
   {{ post.journal }}, {{ post.date | date: "%Y" }}. [PDF]({{ post.pdf_url }})

{% endif %}
{% endfor %}

### CONFERENCE PROCEEDINGS

* Conference Paper 1 (Conference Name, Year) [PDF]
* Conference Paper 2 (Conference Name, Year) [PDF]

### TECHNICAL REPORTS

* Technical Report 1 (Year) [PDF]
* Technical Report 2 (Year) [PDF]

### WORKING PAPERS

* Working Paper 1 (Year) [PDF]