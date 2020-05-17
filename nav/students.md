---
layout: default
title: AISys Lab
permalink: /AISys/
weight: 2
group: members
---

I direct the **Artificial Intelligence and Systems Laboratory (AISys)**. AISys is located at 2212 Storey Innovation Center.

<p align="center">
<a href="{{ site.groupweb }}" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/GitHub-Mark-64px.png" title="AISys GitHub"></a>
<a href="https://dml-lab.slack.com" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/slack.png" title="AISys Slack"></a>
<a href="https://twitter.com/{{ site.twitter }}" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/Twitter_Logo_Blue.png" title="AISys Twitter Handle"></a>
</p>

```inline
At AISys, we investigate a variety of open problems that sit at the intersection of artificial intelligence, machine learning, and computer systems (embedded, cloud, robotics). We investigate the development of novel algorithmic and theoretically principled ML methods for systems problems such as optimizing the performance and energy efficiency of highly-configurable systems. We also look into the design and architecture of system software that treat ML computation as a first-class citizen such as optimizing training and inference. Our overarching goal is to develop the next generation of on-device and cloud-based systems able to perceive, reason and react to complex real-world environments and users with high levels of precision and efficiency. The algorithms that we develop use and extend theory from deep learning and neural networks, transfer learning, representation learning, non-convex optimization, causal learning, reinforcement learning, and robust optimization. We aim to conduct cutting-edge and high impact research through full-stack approaches that encourage lab members with skills in algorithms, systems, statistics, mathematics and software to work closely together to solve critical and practical challenges in the areas at the intersection of AI+Systems.
```

At AISys, fruitful collaborations and constant learning matters a lot to all of us. We have a culture where students frequently collaborate with each other. We typically combine theoretical and empirical insights to build a principled and thorough understanding of key techniques in machine learning, such as deep learning, as well as the challenges we face in this context. Currently, a major theme in our lab is to develop secure, robust, reliable, and performant machine learning systems.

* Are you a **current Ph.D. student** at UofSC interested in working with me? The door of my office is always open and I love discussing research with students, please stop by and let's chat about your interests.

* Are you a **prospective Ph.D. student** interested in working with me? I am always looking for highly-motivated students to join our AISys Lab at UofSC. Please drop me an email and share your interests (reading some of our recent publications would help a lot to get an idea what kind of research we have been doing). If you already have published at top level Systems, ML, or Software Engineering conferences, the chances for you being admitted here is high. If not, don't worry, there would be chances for every one, but you need to show me some evidence of high motivation. I strongly recommend to put one of your previous work that you are really proud of on GitHub and share details with me. This can be in a form of an industrial project, a research project, a replication of the result of a good paper in your area, a replication of one of our recent [papers](/publications/), or even better a contribution to an open source project. Apply to the [CS PhD program](https://www.cse.sc.edu/graduate/admissions) at UofSC. 

* Are you a **prospective Ph.D. student and a US citizen or a permanent resident of the US** interested in working with me? There are some opportunities that you may consider applying and I am happy to work with you on these to secure a grant: e.g., [The DOE Office of Science Graduate Student Research (SCGSR) program](https://science.osti.gov/wdts/scgsr/), [NSF Graduate Research Fellowships Program (GRFP)](https://www.nsfgrfp.org/).

* Are you a **UofSC undergraduate student** interested in working with me on research? Please email me your resume and a description on why you want to get involved. You have a very good chance if: you have contributed to a project in the past (e.g., via a prior experience, or even some personal projects); You have a strong background in computer science and programming (and ideally good in math); You are able to commit 15+ hours/week.

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