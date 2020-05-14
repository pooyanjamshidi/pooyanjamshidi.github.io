---
layout: default
title: Research
weight: 1
group: research
---

```inline
I am an assistant professor in the Computer Science and Engineering department at the University of South Carolina. My goal is to advance a scientific and principled understanding of learning-enabled autonomous systems (e.g., rovers, spacecraft landers) informed by careful empirical and theoretical work. My research is driven by theoretical understanding of machine learning and the mathematics behind statistical learning theory. I am, in particular, interested in transfer and representation learning, with the goal of developing reliable and robust algorithms that enable autonomous agents to learn optimal policies in a way that they can reuse the learned policy to solve similar tasks over varieties of diverse environments. Naturally, I am also interested in connections among computer systems, machine learning, and artificial intelligence. 
```

Prior to joining the faculty at the University of South Carolina, I was a post-doc in the [School of Computer Science](https://www.cs.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/) working with [Christian Kaestner](https://www.cs.cmu.edu/~ckaestne/), and, before that, I was a post-doc in the [Department of Computing](https://www.imperial.ac.uk/computing) at [Imperial College London](https://www.imperial.ac.uk/). I received my Ph.D. from the School of Computing at [Dublin City University](https://www.dcu.ie/) and my advisor was [Claus Pahl](http://www.inf.unibz.it/~cpahl/).

* Want to work with me? Read about [AISys Lab](/AISys/).

* Want to joint our weekly reading group? Read about our [AISys Reading Group](https://github.com/softsys4ai/readingroup/wiki). 

<!-- <table class="table table-sm">

    <tbody><tr>
        <td>8 May 2019</td>
        <td>I am joining the University of Chicago as Neubauer Professor of
            Computer Science and Director of the Center for Data and
            Computing. </td>
    </tr>

    <tr>
        <td>7 May 2019</td>
        <td>Jason Livingood and I posted 
            <a href="https://arxiv.org/abs/1905.02334">an early draft</a> 
            on the challenges for next-generation Internet speed testing. 
        </td>
    </tr>

    <tr>
        <td>1 May 2019</td>
        <td>Marshini Chetty and I gave the <a href="https://www.pds.org/school-news/news-post/~post/pioneers-in-science-at-pds-unpacking-ai-and-machine-learning-20190404">Pioneers in Science lecture</a> at <a href="https://pds.org/">Princeton Day School</a> on applications of Machine Learning in Computer Science.
        </td>
    </tr>

 
     <tr>
        <td>10 Apr 2019</td>
        <td><a href="https://iot-inspector.princeton.edu/">IoT inspector</a>
            (led by postdoc Danny Huang) is officially released!
        </td> 
     </tr>

     <tr>
        <td>4 Apr 2019</td>
        <td>I co-organized an NSF workshop at Princeton on the intersection of
            machine learning and networking ("self-running networks")..</td>
    </tr>


     <tr>
        <td>20 Mar 2019</td>
        <td>I <a href="https://www.ftc.gov/policy/hearings-competition-consumer-protection">testified
                  before the Federal Trade Commission</a> on speed test design
            and Internet architecture.</td>
    </tr>

</tbody></table> -->


### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

<!-- ### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %} -->
