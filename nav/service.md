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


Starting from 2021, my main focus will be on [JSys](http://jsys.org/)---a new diamond open-access journal for the systems community. Please consider submiting your research work to JSys!

### Current
{% include services.html data=current %}

### Past
{% include services.html data=past %}
