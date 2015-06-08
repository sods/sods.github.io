---
layout: page
tagline: open data science initiative
title: Software
---

We have several repositories for software. Some are written by us directly, others are rehosting of code that has disappeared from the web or we are hosting here on the author's behalf.

{% for repository in site.github.public_repositories %}
{% if repository.has_pages %}
{% if repository.name contains 'github.io' %}
{% else %}
* [**{{ repository.name }}**](./{{ repository.name }}/) {{ repository.description }} ({{ repository.watchers_count }} watchers)
{% endif %}
{% endif %}
{% endfor %}

## Other Software in GitHub

The SheffieldML group also makes machine learning software avialble through the [ML@SITraN](http://sheffieldml.github.io/software.html) page, and some of Neil's older software is available from [his page](http://inverseprobability.com/software.html).

Our objective is to releasing software targeted at making open data science easier for both 'generators' and 'consumers' of data science methodologies.

