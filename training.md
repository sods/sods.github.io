---
layout: page
title: Training
tagline: deploying understanding of data and models
---

A key component of our agenda is training and distribution of expertise.

- We run the [Gaussian process summer schools](http://gpss.cc)
- Distributing good research data analysis practice
  - with [Marta Milo](https://www.sheffield.ac.uk/bms/research/milo) from the Department of Biomedical Sciences [Mike Croucher](http://www.walkingrandomly.com/?page_id=2) has been helping to [introduce 2nd year Biomedical Science students](./bioinformatics/) to programming using R and the [jupyter notebook](jupyter.org).


## Meetings

This is a list of meetings we've organised.

{% for meeting in site.data.meetings %}
-  [{{ meeting.event }}]({{ meeting.url }}), {{ meeting.location }}{% if meeting.startday %}, {{ meeting.startday }}{% if meeting.endday %}-{{ meeting.endday }}{% endif %}{% endif %} {{ meeting.startmonth }} {{ meeting.year }} {% if meeting.coorganizers %} (organised with {{ meeting.coorganizers }}){% endif %}
{% endfor %}

