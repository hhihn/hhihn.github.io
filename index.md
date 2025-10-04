---
layout: default
title: Home
---

## Willkommen!
Willkommen auf meiner Seite! Hier könnt ihr mehr über mich und meine Arbeit erfahren. 

### Neuigkeiten

{% for post in site.posts limit:5 %}
- **{{ post.date | date: "%B %d, %Y" }}**: {{ post.title }}
  {% endfor %}

### Links

* [Über mich](/about)
* [Forschung](/research)
* [Publikationen](/publications)
* [Kontakt](/contact)

### Aktuelle Publikationen

* Project Alpha - Description here
* Project Beta - Another description
* Project Gamma - Yet another project

*Last updated: January 1999*