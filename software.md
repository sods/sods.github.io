---
layout: page
tagline: open data science initiative
title: Software
---

{% for repository in site.github.public_repositories %}
{% if repository.has_pages %}
{% if repository.name contains 'github.io' %}
{% else %}
* [**{{ repository.name }}**](./{{ repository.name }}/) {{ repository.description }} ({{ repository.watchers_count }} watchers)
{% endif %}
{% endif %}
{% endfor %}

We have two main outlets for our software, in the [SheffieldML](https://github.com/SheffieldML/) github organisation we are mainly releasing new machine learning methodologies and in the [SODS](https://github.com/sods/) repository (software for open data science) we are releasing software targeted at making open data science easier for both 'generators' and 'consumers' of data science methodologies.

