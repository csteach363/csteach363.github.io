---
title: COMP 363
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: Design and Analysis of Computer Algorithms, Spring 2020
---

Welcome to the course website for COMP 363.

This course is offered by the [Department of Computer Science](http://www.luc.edu/cs/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}

<!--{{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})-->
* {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})

  {{ post.summary }}

{% endfor %}
