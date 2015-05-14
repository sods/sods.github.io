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

The SheffieldML group also makes machine learning software avialble through the [SheffieldML](https://github.com/SheffieldML/) github organisation. We are releasing software targeted at making open data science easier for both 'generators' and 'consumers' of data science methodologies.

