---
layout: default
title: Home
weight: 1
group: research
---

```inline
I am an Assistant Professor in the Computer Science and Engineering department at the University of South Carolina. I do research at the intersection of AI/ML + Systems = AISys. My goal is to advance a scientific and principled understanding of learning-enabled autonomous systems (e.g., Space Rovers/Landers). My research is driven by a theoretical understanding of machine learning systems and the mathematics behind the statistical learning theory. I am, in particular, interested in transfer learning, with the goal of developing robust algorithms that enable autonomous systems to learn causal invariance to accelerate learning and solve varieties of tasks in diverse environments.
```

Prior to joining the faculty at the University of South Carolina, I was a post-doc in the [School of Computer Science](https://www.cs.cmu.edu/) at [Carnegie Mellon University](https://www.cmu.edu/) working with [Christian Kaestner](https://www.cs.cmu.edu/~ckaestne/), and, before that, I was a post-doc in the [Department of Computing](https://www.imperial.ac.uk/computing) at [Imperial College London](https://www.imperial.ac.uk/). I received my Ph.D. from the School of Computing at [Dublin City University](https://www.dcu.ie/) and my advisor was [Claus Pahl](http://www.inf.unibz.it/~cpahl/).

* I have an ``open office`` policy (even after the pandemic!) You can book an appointment with me [here](https://meet-with-pooyan-jamshidi.appointlet.com/s/15-minute-intro/pooyan-jamshidi).

* Want to ``work with us``? Read about [AISys Lab](/AISys/).

* Want to joint our weekly ``reading group``? Read about our [AISys Reading Group](https://github.com/softsys4ai/readingroup/wiki). 

###  News

<table class="table table-sm">

    <tbody>
    <tr>
        <td>14 Sept 2020</td>
        <td> I am thrilled that <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2007202">SmartSight: an AI-Based Computing Platform to Assist Blind and Visually Impaired People</a> has been funded by NSF. This is a collaborative <strong>AI for Social Good</strong> project in collaboration with <a href="https://people.cmix.louisiana.edu/amini/">Mohsen Amini Salehi</a> with total funding of $499,650. This project is aligned to our <a href="https://pooyanjamshidi.github.io/diversity/">diversity</a> efforts. Thanks <strong>NSF</strong>!</td>
    </tr>
    <tr>
        <td>1Sept 2020</td>
        <td>I gave an invited talk to Googlers as a part of <strong>Let's Talk Tech</strong> series on <a href="https://speakerdeck.com/pjamshidi/ensembles-of-many-diverse-weak-defenses-can-be-strong">Ensembles of Many Diverse Weak Defenses can be Strong</a>. Thanks <strong>Google</strong>!</td>
    </tr>
    <tr>
        <td>20Aug 2020</td>
        <td>I am so honored to join the <strong>ACM TOSEM Board of Distinguished Reviewers</strong>, I am so thankful to the associate editor who nominated me for this role!</td>
    </tr>
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
</tbody></table>
<a href="/news">Older News...</a>

### Current Projects
{% assign current = site.data.projects | where_exp: "project", "project.end == nil" %}
{% include projects.html data=current %}

<!-- ### Inactive Projects
{% assign inactive = site.data.projects | where_exp: "project", "project.end != nil" %}
{% include projects.html data=inactive %} -->
