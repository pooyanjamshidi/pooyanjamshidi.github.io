---
layout: default
title: AISys Lab
permalink: /AISys/
weight: 3
group: members
---

I direct the **Artificial Intelligence and Systems Laboratory (AISys)**. AISys is located at 2212 and 1211 in Storey Innovation Center.

```inline
The AISys lab welcomes people of any race, religion, national origin, gender identity, family commitments, political affiliation, sexual orientation, and eligible age or ability.
```

<p align="center">
<a href="{{ site.groupweb }}" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/GitHub-Mark-64px.png" title="AISys GitHub"></a>
<a href="https://dml-lab.slack.com" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/slack.png" title="AISys Slack"></a>
<!-- <a href="https://twitter.com/{{ site.twitter }}" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/Twitter_Logo_Blue.png" title="AISys Twitter Handle"></a> -->
</p>

```inline
We investigate a variety of open problems that sit at the intersection of artificial intelligence, machine learning, and computer systems. We investigate the development of novel algorithmic and theoretically principled methods that are grounded in mathematics for systems problems with the ultimate goal of building reliable and high-performance machine learning systems. On the application side, we aim to develop the next generation of autonomous systems (on-device, embedded, heterogeneous, cloud, robotics) that can perceive, reason, and react to complex real-world environments and users with high levels of precision and efficiency. Overall, we aim to conduct cutting-edge and high-impact research through full-stack approaches that encourage lab members with skills in algorithms, systems, and math to solve critical and practical challenges at the intersection of AI+Systems.
```


<p align="center">
  <img width="1000px" height="auto" src="/resources/images/groupphotos/group-photo-nov-2020.jpg">
  <img width="1000px" height="auto" src="/resources/images/groupphotos/group-photo-feb-2020.jpg">
</p>


<!-- 
```inline
Core technical areas: Transfer learning, representation learning, deep learning, non-convex optimization, causal inference, reinforcement learning, concept learning, and robust optimization.
``` -->

### Core Values 

* Fruitful *collaborations* and constant *learning* matter a lot to all of us. 
* We combine *theoretical* and *empirical* insights to build intelligent autonomous systems.
* We start by *hypothesis*, we design experiments, and use theory to understand the empirical *observations*.
* *Understanding* the causal mechanisms and governing dynamics of [machine learning systems](/mls) inspires us.
* Scientific *rigor* is a principal value.
* We all *love* what we do, proud of *what* we bring into the world, and *how* we build it. 
* We love to give and receive regular feedback, this helps us to constantly learn and improve our outcomes.
* Everyone is of equal value. *Fairness* and *equality* matter to us a lot.
* Our [*diversity*](/diversity) is important and will be an ongoing goal.
* Transparency and *open access* to scientific outcomes is key to make progress, we release all [code+data][github].
* Our lab is open to all people of any *beliefs* and *ideas*.
* We are weird in one way or another, but we do respect *math*!
* *Reproducible* science is what we care the most.
* All above values start with *respect* to science, colleagues, lab members, and all people.
* We also have lots of fun times, checkout [our group photos](https://www.flickr.com/photos/uofsccec/sets/72157713000257436/) over time, before and after the pandemic!



<!-- Currently, a major theme in our lab is to develop secure, robust, reliable, and performant machine learning systems. -->

### For prospective AISys members

* Are you a **current Ph.D. student** at UofSC interested in working with me? The door of my office is always open and I love discussing research with students, please stop by and let's chat about your interests.

* Are you a **prospective Ph.D. student** interested in working with me? I am always looking for highly-motivated students to join our AISys Lab at UofSC. Please drop me an email and share your interests (reading some of our recent publications would help a lot to get an idea of what kind of research we have been doing). If you already have published at top-tier Systems, ML, or Software Engineering conferences, the chances for you to be admitted here are high. If not, don't worry, there would be chances for everyone, but you need to show me some evidence of high motivation. I strongly recommend to put one of the previous work that you are proud of on GitHub and share details with me. This can be in a form of an industrial project, a research project, a replication of the result of a good paper in your area, a replication of one of our recent [papers](/publications/), or even better a contribution to an open-source project. Apply to the [CS Ph.D. program](https://www.cse.sc.edu/graduate/admissions) at UofSC. 

  - If you are *a US citizen or a permanent resident of the US* there are some opportunities that you may consider applying and I am happy to work with you on these to secure a grant: e.g., [NSF Graduate Research Fellowships Program (GRFP)](https://www.nsfgrfp.org/), and [The DOE Office of Science Graduate Student Research (SCGSR) program](https://science.osti.gov/wdts/scgsr/).

* Are you a **UofSC undergraduate student** interested in working with me on research? Please email me your resume and a description of why you want to get involved. You have a very good chance if: you have contributed to a project in the past (e.g., via prior experience, or even some personal projects); You have a strong background in computer science and programming (and ideally good in math); You can commit 15+ hours/week.


<!-- Here are members of AISys research lab, including postdocs, doctoral, and masters students, as well as undergrad research assistants. I am always looking for highly-motivated students (on all levels) to join our AISys Lab at USC. -->




### Current Members
{% assign current = site.data.members | where:"status","current" %}
{% include members.html data=current %}

<!-- ### Affiliated Members
{% assign affiliated = site.data.members | where:"status","affiliated" %}
{% include members.html data=affiliated %} -->

### Former Members
{% assign former = site.data.members | where:"status","former" %}
{% include members.html data=former %}


[github]: {{ site.groupweb | prepend: site.baseurl }}