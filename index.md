---
layout: default
title: Home
weight: 1
group: research
---

```inline
I am an assistant professor in the Computer Science and Engineering department at the University of South Carolina. My goal is to advance a scientific and principled understanding of learning-enabled autonomous systems (e.g., rovers, spacecraft landers) informed by careful empirical and theoretical work. My research is driven by a theoretical understanding of machine learning and the mathematics behind statistical learning theory. I am, in particular, interested in transfer and representation learning, with the goal of developing reliable and robust algorithms that enable autonomous systems to learn optimal policies in a way that they can reuse the learned policy to solve similar tasks over varieties of diverse environments. Naturally, I am also interested in connections between computer systems, machine learning, and artificial intelligence. 
```

Prior to joining the faculty at the University of South Carolina, I was a post-doc in the [School of Computer Science](https://www.cs.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/) working with [Christian Kaestner](https://www.cs.cmu.edu/~ckaestne/), and, before that, I was a post-doc in the [Department of Computing](https://www.imperial.ac.uk/computing) at [Imperial College London](https://www.imperial.ac.uk/). I received my Ph.D. from the School of Computing at [Dublin City University](https://www.dcu.ie/) and my advisor was [Claus Pahl](http://www.inf.unibz.it/~cpahl/).

* Want to work with me? Read about [AISys Lab](/AISys/).

* Want to joint our weekly reading group? Read about our [AISys Reading Group](https://github.com/softsys4ai/readingroup/wiki). 

###  News

<table class="table table-sm">

    <tbody>
    <tr>
        <td>4Aug 2020</td>
        <td>I am thrilled that our project, <strong>Autonomous Robotics Research for Ocean Worlds (ARROW)</strong>, has been awarded by <strong>NASA</strong>. This exciting project is lead by UofSC, in collaboration with CMU, York, Arkansas, and NASA.</td>
    </tr>
    <tr>
        <td>6July 2020</td>
        <td>"AMP Chain Graphs: Minimal Separators and Structure Learning Algorithms" was accepted at <strong>Journal of Artificial Intelligence Research</strong>. Congratulations <a href="/AISys/#javidian">Mohammad Ali Javidian</a>! </td>
    </tr>

    <tr>
        <td>14May 2020</td>
        <td> "Learning LWF Chain Graphs: A Markov Blanket Discovery Approach" was accepted at <strong>UAI 2020</strong>. Congratulations <a href="/AISys/#javidian">Mohammad Ali Javidian</a>! </td>
    </tr>

    <tr>
        <td>13May 2020</td>
        <td>I was invited to serve on a <strong>NSF panel</strong> (CISE/IIS). Thanks NSF! </td>
    </tr>

    <tr>
        <td>10May 2020</td>
        <td>I am thrilled that our project, <strong>A Generic Data-Driven Framework via Physics-Informed Deep Learning</strong>, has been awarded. PI: Lang Yuan. Thanks <strong>NASA</strong> for supporting our work! 
        </td>
    </tr>
</tbody></table>
<a href="/news">Older News...</a>

### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

<!-- ### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %} -->
