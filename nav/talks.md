---
layout: default
title: Talks
permalink: /talks/
weight: 5
group: talks
---

# Invited Talks

I upload my presentations in [SlideShare](https://www.slideshare.net/pooyanjamshidi).


{% assign talk_by_year = site.data.talks | group_by_exp:"talk", "talk.year | plus: 0" %}
{% for year in talk_by_year %}
  {% for talk in year.items %}
  <div class="publication" id="{{ talk.id }}">
    <div class="talk-title">
      <div class="row-pic">
        {% include /functions/gettalkpic.html talk=talk %}
  	  </div>
      <a href="{{ talk.url }}"> {{ talk.title }} </a> <br>
      <em>{{ talk.where }}</em>, {{ talk.month }}, {{ talk.year }} <br>
      {% if talk.video %}
      [<a href="{{ talk.video }}"> Video </a>]
      {% endif %}
    </div>
  </div>
  {% endfor %}
{% endfor %}







<!-- * [Ensembles of Many Diverse Weak Defenses can be Strong: Defending Deep Neural Networks Against Adversarial Attacks](https://www.slideshare.net/pooyanjamshidi/ensembles-of-many-diverse-weak-defenses-can-be-strong-defending-deep-neural-networks-against-adversarial-attacks), Augusta University, Augusta, Georgia, February 2020. -->

<!-- * [Transfer Learning for Performance Analysis of Machine Learning Systems](https://www.slideshare.net/pooyanjamshidi/transfer-learning-for-performance-analysis-of-machine-learning-systems), Furman University, Greenville, South Carolina, April 2019. -->

<!-- * [Machine Learning meets DevOps: Transfer Learning for Performance Optimization](https://www.slideshare.net/pooyanjamshidi/machine-learning-meets-devops-124313812), Machine Learning for DevOps Summit, Houston, Texas, November 2018. -->

<!-- * [Architectural Tradeoffs in Learning-Based Software](https://www.slideshare.net/pooyanjamshidi/architectural-tradeoff-in-learningbased-software), SATURN'18, Plano, Texas, May 2018. -->

<!-- * [Transfer Learning for Software Performance Analysis: An Exploratory Analysis](https://www.slideshare.net/pooyanjamshidi/transfer-learning-for-software-performance-analysis-an-exploratory-analysis), Urbana-Champaign, IL, November 2017. -->

<!-- * [Architecting for Scale](https://www.slideshare.net/pooyanjamshidi/architecting-for-scale-80515767), Invited lecture at CMU, Pittsburgh, PA, October 2017. -->

<!-- * [Learning Software Performance Models for Dynamic and Uncertain Environments](https://www.slideshare.net/pooyanjamshidi/learning-software-performance-models-for-dynamic-and-uncertain-environments-76616004), Raleigh, NC, June 2017. -->

<!-- * [Transfer Learning for Improving Model Predictions in Highly Configurable Software](https://www.slideshare.net/pooyanjamshidi/transfer-learning-for-improving-model-predictions-in-highly-configurable-software), DARPA Workshop, Boston, MA, March 2017. -->

<!-- * [An Uncertainty-Aware Approach to Optimal Configuration of Stream Processing Systems](https://www.slideshare.net/pooyanjamshidi/an-uncertaintyaware-approach-to-optimal-configuration-of-stream-processing-systems), Bern University, Bern, Switzerland, November 2016. -->

<!-- * [Machine Learning meets DevOps](https://www.slideshare.net/pooyanjamshidi/machine-learning-meets-devops), Dagstuhl seminar (Software Performance Engineering in the DevOps World), Dagstuhl, Germany, September 2016. -->

<!-- * [Transfer Learning for Optimal Configuration of Big Data Software](https://www.slideshare.net/pooyanjamshidi/transfer-learning-for-optimal-configuration-of-big-data-software), Imperial College London, UK, June 2016. -->

<!-- * [Microservices Architecture Enables DevOps: Migration to a Cloud-Native Architecture](https://www.slideshare.net/pooyanjamshidi/microservices-architecture-enables-devops-migration-to-a-cloudnative-architecture), Online talk, RG DevOps Performance Working Group, March 2016. -->

<!-- * [Fuzzy Self-Learning Controllers for Elasticity Management in Dynamic Cloud Architectures](https://www.slideshare.net/pooyanjamshidi/fuzzy-selflearning-controllers-for-elasticity-management-in-dynamic-cloud-architectures), National Institute of Informatics (NII), Controlled Adaptation of Self-adaptive Systems (CASaS), Shonan, Japan, April 2016. -->

<!-- * [Self-learning Cloud Controllers](https://www.slideshare.net/pooyanjamshidi/self-learning-cloud-controllers), Online talk, RG DevOps Performance Working Group, February 2015;  Trinity College Dublin, Dublin, Ireland, February 2015; Federal University of Ceará, Fortaleza, Brazil, January 2015. -->

<!-- * [Cloud Migration Patterns: A Multi-Cloud Architectural Perspective](https://www.slideshare.net/pooyanjamshidi/cloud-migrationpatterns), Ceará State University, Fortaleza, Brazil, January 2015. -->

<!-- * [Fuzzy Control meets Software Engineering](https://www.slideshare.net/pooyanjamshidi/dagstuhl-pooyan), Dagstuhl seminar (Control Theory meets Software Engineering), Dagstuhl, Germany, September 2014. -->