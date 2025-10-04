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

### Aktuelle Publikationen

* Hihn, H., Dittrich, D. A., Jeske, C., Sobral, C. C., Pais, H., & Lochmann, T. (2025). Ontology-Aligned Embeddings for Data-Driven Labour Market Analytics. SIG Knowledge Management Workshop (FG WM) at KI2025, Potsdam, Germany
* Hihn, H., & Braun, D. A. (2024). Online continual learning through unsupervised mutual information maximization. Neurocomputing, 578, 127422.
* Hihn, H., & Braun, D. A. (2023). Hierarchically structured task-agnostic continual learning. Machine Learning, 112(2), 655-686.

*Zuletzt aktualisiert: Januar 1999*