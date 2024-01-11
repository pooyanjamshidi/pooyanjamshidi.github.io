---
layout: default
title: Service
navtitle: Service
permalink: /service/
weight: 9
group: service
---

{% assign thisYear = "now" | date: "%Y" | plus: 0 %}
{% assign current = site.data.services | where_exp: "service", "service.year >= thisYear"%}
{% assign past = site.data.services | where_exp: "service", "service.year < thisYear"%}

## Journals and Editorials

I am committed to open-access publication venues, and I only accept to serve in venues and communities that are committed to open science. 

* I serve as an Associate Editor of [ACM Transactions on Software Engineering and Methodology (TOSEM)](https://dl.acm.org/journal/tosem). Please consider submitting your ``Software Engineering research`` to TOSEM!

* With other colleagues, we co-founded [JSys](http://jsys.org/)---a new diamond open-access journal for the systems community. I also serve as an area co-chair at JSys. Please consider submitting your ``Computer Systems research`` to JSys!

## Conferences

### Current
{% include services.html data=current %}

### Past
{% include services.html data=past %}
