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

###  News
<!-- <pre>
<code>
<li> <em>May. 14, 2020</em>: A paper (Learning LWF Chain Graphs: A Markov Blanket Discovery Approach) was accepted at <strong>UAI 2020</strong>. Congratulations Mohammad Ali Javidian!</li>
<li> <em>Apr. 10, 2020</em>: A <strong>NASA grant</strong> (A Generic Data-Driven Framework via Physics-Informed Deep Learning) was awarded. PI: Lang Yuan. Thanks NASA for supporting our work!</li>
<a href="/news">Older News...</a>
</code>
</pre> -->

<table class="table table-sm">

    <tbody><tr>
        <td>6 July 2020</td>
        <td>A paper ("AMP Chain Graphs: Minimal Separators and Structure Learning Algorithms") was accepted at <strong>Journal of Artificial Intelligence Research</strong>. Congratulations <a href="/AISys/#javidian">Mohammad Ali Javidian</a>! </td>
    </tr>

    <tr>
        <td>14 May 2020</td>
        <td>A paper ("Learning LWF Chain Graphs: A Markov Blanket Discovery Approach") was accepted at <strong>UAI 2020</strong>. Congratulations <a href="/AISys/#javidian">Mohammad Ali Javidian</a>! </td>
    </tr>

    <tr>
        <td>13 May 2020</td>
        <td>I was invited to serve on a <strong>NSF panel</strong> (CISE/IIS). Thanks NSF! </td>
    </tr>

    <tr>
        <td>10 May 2020</td>
        <td>A <strong>NASA grant</strong> ("A Generic Data-Driven Framework via Physics-Informed Deep Learning") was awarded. PI: Lang Yuan. Thanks NASA for supporting our work! 
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
