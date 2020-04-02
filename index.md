---
layout: default
title: Research
weight: 1
group: research
---

I am an assistant professor in the Computer Science and Engineering Department at the University of South Carolina. My goal is to advance a scientific and principled understanding of learning-enabled autonomous systems (e.g., rovers, spacecraft landers) informed by careful empirical and theoretical work. My research is driven by theoretical understanding of machine learning and the mathematics behind statistical learning theory. I am, in particular, interested in transfer and representation learning, with the goal of developing reliable and robust algorithms that enable autonomous agents to learn optimal policies in a way that they can reuse the learned policy to solve similar tasks over varieties of diverse environments. Naturally, I am also interested in connections among **computer systems, machine learning, and artificial intelligence**. 

Prior to joining the faculty at the University of South Carolina, I was a post-doc in the [School of Computer Science](https://www.cs.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/) working with [Christian Kaestner](https://www.cs.cmu.edu/~ckaestne/), and, before that, I was a post-doc in the [Department of Computing](https://www.imperial.ac.uk/computing) at [Imperial College London](https://www.imperial.ac.uk/). I received my Ph.D. from the School of Computing at [Dublin City University](https://www.dcu.ie/) and my advisor was [Claus Pahl](http://www.inf.unibz.it/~cpahl/).

Want to work with me? Read about [AISys Lab](/AISys/).

Want to joint our weekly reading group? Read about our [AI+Systems Reading Group](https://github.com/softsys4ai/readingroup/wiki). 

### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

<!-- ### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %} -->
