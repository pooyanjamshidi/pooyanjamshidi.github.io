---
layout: default
title: Research
weight: 1
group: research
---

I am an assistant professor in the Computer Science and Engineering Department at the University of South Carolina. My goal is to advance a scientific, principled understanding of Artificial Intelligence and Machine Learning Systems, with an eye towards computer systems analysis (e.g., understanding their performance behavior, reasoning about qualities and making tradeoff) informed by careful empirical work. Naturally, I am also interested in connections among computer systems, AI/ML, and software engineering. I am always looking for highly-motivated students to join our [AISys Lab](/AISys/) at USC.


### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

<!-- ### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %} -->
