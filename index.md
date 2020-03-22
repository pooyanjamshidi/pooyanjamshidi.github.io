---
layout: default
title: Research
weight: 1
group: research
---

I am an assistant professor in the Computer Science and Engineering Department at the University of South Carolina. My goal is to advance a scientific, principled understanding of **learning-enabled autonomous systems** (e.g., rovers, spacecraft landers), with an eye towards computer systems analysis (e.g., understanding their performance behavior, reasoning about qualities and making tradeoff) informed by careful empirical work. My research is driven by careful **theoretical understanding** of machine learning systems and the **mathematics** behind statistical learning theory. Naturally, I am also interested in connections among **computer systems and machine learning**. 

Want to work with me? Read about [AISys Lab](/AISys/).

Want to joint our weekly reading group? Read about our [AI+Systems Reading Group](https://github.com/softsys4ai/readingroup/wiki). 

### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

<!-- ### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %} -->
