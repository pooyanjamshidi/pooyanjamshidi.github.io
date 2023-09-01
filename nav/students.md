---
layout: default
title: AISys Lab
permalink: /AISys/
weight: 3
group: members
---

I direct the **Artificial Intelligence and Systems Laboratory (AISys)**. AISys is located at 2212 and 1211 in Storey Innovation Center.

A research overview of AISys lab can be found [here](https://speakerdeck.com/pjamshidi/artificial-intelligence-and-systems-laboratory-aisys-a-research-overview).

```inline
The AISys lab welcomes people of any race, religion, national origin, gender identity, family commitments, political affiliation, sexual orientation, and eligible age or ability.
```

<p align="center">
<a href="{{ site.groupweb }}" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/GitHub-Mark-64px.png" title="AISys GitHub"></a>
<a href="https://dml-lab.slack.com" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/slack.png" title="AISys Slack"></a>
<!-- <a href="https://twitter.com/{{ site.twitter }}" target="_blank"><img width="30" height="30" hspace="20" src="/resources/images/Twitter_Logo_Blue.png" title="AISys Twitter Handle"></a> -->
</p>

```inline
We investigate various open problems at the intersection of artificial intelligence, machine learning, and computer systems. We develop novel algorithmic and theoretically principled methods grounded in mathematics for systems problems with the ultimate goal of building reliable and high-performance machine learning systems. On the application side, we aim to develop the next generation of autonomous systems (on-device, embedded, heterogeneous, cloud, robotics) that can perceive, reason, and react to complex real-world environments and users with high levels of precision and efficiency. Overall, we aim to conduct cutting-edge and high-impact research through full-stack approaches that encourage lab members with algorithms, systems, and math skills to solve critical and practical challenges at the intersection of AI+Systems.
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
* We start by *hypothesis*, designing experiments, and use theory to understand the empirical *observations*.
* *Understanding* the causal mechanisms and governing dynamics of [machine learning systems](/mls) inspires us.
* Scientific *rigor* is a principal value.
* We all *love* what we do, proud of *what* we bring into the world, and *how* we build it. 
* We love to give and receive regular feedback; this helps us constantly learn and improve our outcomes.
* Everyone is of equal value. *Fairness* and *equality* matter to us a lot.
* Our [*diversity*](/diversity) is important and will be an ongoing goal.
* Transparency and *open access* to scientific outcomes are key to making progress; we release all [code+data][github].
* Our lab is open to all people of any *beliefs* and *ideas*.
* We are weird in one way or another, but we do respect *math*!
* *Reproducible* science is what we care about the most.
* All the above values start with *respect* for science, colleagues, lab members, and everyone.
* We also have lots of fun times; check out [our group photos](https://www.flickr.com/photos/uofsccec/sets/72157713000257436/) over time, before and after the pandemic!



<!-- Currently, a major theme in our lab is to develop secure, robust, reliable, and performant machine learning systems. -->

### For prospective AISys members
* **Update:** As of January 2023, I do not plan to hire any Ph.D. student until further notice; Please feel free to apply for our graduate school and contact my colleagues and collaborators; I am so sorry that I may not be able to answer prospective student emails asking for available positions at AISys.

* Are you a **current Ph.D. student** at UofSC interested in working with me or brainstorming about research ideas? My office door is always open, and I love discussing research with students; please stop by and let's chat about your interests.

* Are you a **prospective Ph.D. student** interested in working with me? I always look for highly motivated students to join our AISys Lab at UofSC. Please drop me an email and share your interests (reading some of our recent publications would help a lot to get an idea of what kind of research we have been doing). If you have already published at top-tier Systems, ML, or Software Engineering conferences, the chances for you to be admitted here are high. If not, don't worry, there would be chances for everyone, but you must show me evidence of high motivation. I recommend putting one of the previous works you are proud of on GitHub and sharing details with me. This can be in the form of an industrial project, a research project, a replication of the result of a good paper in your area, a replication of one of our recent [papers](/publications/), or even better, a contribution to an open-source project. Apply to the [CS Ph.D. program](https://www.cse.sc.edu/graduate/admissions) at UofSC. 

  - If you are *a US citizen or a permanent resident of the US* there are some opportunities you may consider applying for. I am happy to work with you on these to secure a grant: e.g., [The NSF Graduate Research Fellowships Program (GRFP)](https://www.nsfgrfp.org/) and [The DOE Office of Science Graduate Student Research (SCGSR) program](https://science.osti.gov/wdts/scgsr/).

* Are you a **UofSC undergraduate student** interested in working with me on research? Please email me your resume and describe why you want to get involved. You have an excellent chance if: you have contributed to a project in the past (e.g., via prior experience or even some personal projects); You have a strong background in computer science and programming (and are ideally confident in math); You can commit 15+ hours/week.



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