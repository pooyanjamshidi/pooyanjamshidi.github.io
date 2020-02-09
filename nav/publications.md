---
layout: default
title: Publications
navtitle: Publications
permalink: /publications/
weight: 3
group: publications
---

These are my academic publications.
* A more comprehensive list of my publications can be find in [Google Scholar](http://scholar.google.com/citations?hl=en&user=Jre2RUQAAAAJ)
* I regularly upload all PDF version of my publications in [Research Gate](https://www.researchgate.net/profile/Pooyan_Jamshidi)
* I upload my presentations in [SlideShare](https://www.slideshare.net/pooyanjamshidi)
* I indicate my representative publications with <span style="color: red">&#9733;</span>
 
 <!-- <a href="https://www.researchgate.net/profile/Pooyan_Jamshidi">Research Gate</a>, <a href="https://www.slideshare.net/pooyanjamshidi">SlideShare</a> -->

<!-- <script src="https://bibbase.org/show?bib=https://dblp.org/pid/57/2301.bib&jsonp=1"></script>
 -->

<!-- <script src="https://bibbase.org/show?bib=dl.dropboxusercontent.com/s/0gvbm4fasnl0r5l/Jamshidi_Pooyan.bib&jsonp=1&authorFirst=1&token=8ce1b3e11a6bf5722096eb05adee869b&fullnames=1">
</script> -->


{% assign papers_by_year = site.data.papers | group_by_exp:"paper", "paper.year | plus: 0" %}
{% for year in papers_by_year %}
  <h3>{{ year.name }}</h3>
  {% for paper in year.items %}
  <div class="publication" id="{{ paper.id }}">
    {% if paper.award %}
    <span class="icon">
      <svg><use xlink:href="#icon-award"/></svg>
      <b>{{ paper.award }}</b>
    </span> <br/>
    {% endif %}
    <div class="publication-title">
      <div class="row-pic">
        {% include /functions/getpaperpic.html paper=paper %}
  	  </div>
  	  {% if paper.important %}
  	    <span style="color: red">&#9733;</span>
  	  {% endif %}
      <a href="{{ paper.url }}"> {{ paper.title }} </a> <br>
      {{ paper.authors }} <br>
      <em>{{ paper.venue }}</em>
    </div>
    <div class="right">
      <a href="{{ "/resources/papers/" | append: paper.id | append: ".pdf" | prepend: site.baseurl }}" target="_blank">
        <span class="icon"><svg><use xlink:href="#icon-pdf"/></svg></span>
      </a>
      {% if paper.code %}
      <a href="{{ paper.code }}" target="_blank">
        <span class="icon"><svg><use xlink:href="#icon-github"/></svg></span>
      </a>
      {% endif %}
      {% if paper.slide %}
      <a href="{{ paper.slide }}" target="_blank">
        <span class="icon"><svg><use xlink:href="#icon-slides"/></svg></span>
      </a>
      {% endif %}
      {% if paper.video %}
      <a href="{{ paper.video }}" target="_blank">
        <span class="icon"><svg><use xlink:href="#icon-youtube"/></svg></span>
      </a>
      {% endif %}
    </div>
  </div>
  {% endfor %}
{% endfor %}