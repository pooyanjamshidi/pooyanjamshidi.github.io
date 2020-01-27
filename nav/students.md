---
layout: default
title: AISys Lab
permalink: /AISys/
weight: 2
group: members
---

<figure>
	<img style="display=inline-block" width="50%" src="{{ "/resources/images/mls-logo.jpg" |  prepend: site.baseurl }}" alt="AISys Lab" />
</figure>

AISys Lab (Artificial Intelligence and Systems Laboratory) investigates a variety of open problems that sit at the intersection of artificial intelligence (AI), machine learning (ML), and computer systems (e.g., embedded, cloud, robotics). We investigate the development of novel algorithmic and theoretically principled ML methods for systems problems such as optimizing the performance and energy efficiency of highly-configurable systems. We also look into the design and architecture of system software that treat ML computation as a first-class citizen such as optimizing training and inference. Our overarching goal is to develop the next generation of on-device and cloud-based systems able to perceive, reason and react to complex real-world environments and users with high levels of precision and efficiency. We aim to conduct cutting-edge and high impact research through full-stack approaches that encourage lab members with skills in algorithms, systems, statistics, mathematics and software to work closely together to solve critical and practical challenges in the areas at the intersection of AI+Systems.

<!-- Here are members of AISys research lab, including postdocs, doctoral, and masters students, as well as undergrad research assistants. I am always looking for highly-motivated students (on all levels) to join our AISys Lab at USC. -->

### Current Members
{% assign current = site.data.members | where:"status","current" %}
{% include members.html data=current %}

### Affiliated Members
{% assign affiliated = site.data.members | where:"status","affiliated" %}
{% include members.html data=affiliated %}

### Former Members
{% assign former = site.data.members | where:"status","former" %}
{% include members.html data=former %}
