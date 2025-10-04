---
layout: default
title: Home
---

## WELCOME TO MY RESEARCH HOMEPAGE!

Hello and welcome to my homepage! I am {{ site.name }}, a researcher at {{ site.institution }}.

### NEWS & UPDATES

{% for post in site.posts limit:5 %}
- **{{ post.date | date: "%B %d, %Y" }}**: {{ post.title }}
  {% endfor %}

### QUICK LINKS

* [Learn more about me](/about)
* [View my research projects](/research)
* [Browse my publications](/publications)
* [Get in touch](/contact)

### CURRENT PROJECTS

* Project Alpha - Description here
* Project Beta - Another description
* Project Gamma - Yet another project

*Last updated: January 1999*