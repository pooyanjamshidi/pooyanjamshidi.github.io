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

I direct the **Artificial Intelligence and Systems Laboratory (AISys)**.

At AISys, we investigate a variety of open problems that sit at the intersection of artificial intelligence (AI), machine learning (ML), and computer systems (e.g., embedded, cloud, robotics). We investigate the development of novel algorithmic and theoretically principled ML methods for systems problems such as optimizing the performance and energy efficiency of highly-configurable systems. We also look into the design and architecture of system software that treat ML computation as a first-class citizen such as optimizing training and inference. Our overarching goal is to develop the next generation of on-device and cloud-based systems able to perceive, reason and react to complex real-world environments and users with high levels of precision and efficiency. We aim to conduct cutting-edge and high impact research through full-stack approaches that encourage lab members with skills in algorithms, systems, statistics, mathematics and software to work closely together to solve critical and practical challenges in the areas at the intersection of AI+Systems. At AISys, we have a culture where students frequently collaborate with each other.

* Are you a **current Ph.D. student** at UofSC interested in working with me**?** The door of my office is always open and I love discussing research with students, please stop by and let's chat about your interests.

* Are you a **prospective Ph.D. student** interested in working with me**?** I am always looking for highly-motivated students to join our AISys Lab at UofSC. Please drop me an email and share your interests (reading some of our recent publications would help a lot to get an idea what kind of research we have been doing). Apply to the [CS PhD program](https://www.cse.sc.edu/graduate/admissions) at UofSC. 

* Are you a **UofSC undergraduate student** interested in working with me on research**?** Please email me your resume and a description on why you want to get involved. You have a very good chance if: you have contributed to a project in the past (e.g., via a prior experience, or even some personal projects); You have a strong background in computer science and programming (and ideally good in math); You are able to commit 15+ hours/week.

<!-- Here are members of AISys research lab, including postdocs, doctoral, and masters students, as well as undergrad research assistants. I am always looking for highly-motivated students (on all levels) to join our AISys Lab at USC. -->




### Current Members
{% assign current = site.data.members | where:"status","current" %}
{% include members.html data=current %}

<!-- ### Affiliated Members
{% assign affiliated = site.data.members | where:"status","affiliated" %}
{% include members.html data=affiliated %}

### Former Members
{% assign former = site.data.members | where:"status","former" %}
{% include members.html data=former %}
 -->