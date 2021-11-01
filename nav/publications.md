---
layout: default
title: Publications
navtitle: Publications
permalink: /publications/
weight: 4
group: publications
---

These are my ``notable`` academic publications.
* A more comprehensive list of my publications can be find in [Google Scholar](http://scholar.google.com/citations?hl=en&user=Jre2RUQAAAAJ&view_op=list_works&sortby=pubdate)
* I regularly upload all PDF version of my publications in [Research Gate](https://www.researchgate.net/profile/Pooyan_Jamshidi)
* I upload my presentations in [SlideShare](https://www.slideshare.net/pooyanjamshidi) or [SpeakerDeck](https://speakerdeck.com/pjamshidi).
* Selected publications are indicated with <span style="color: red">&#9733;</span>
* Nominated or best paper awards are indicated with <span class="icon"> <svg><use xlink:href="#icon-award"/></svg></span>
 
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
    <div class="publication-title">
      <div class="row-pic">
        {% include /functions/getpaperpic.html paper=paper %}
  	  </div>
  	  {% if paper.award %}
        <span class="icon">
        <svg><use xlink:href="#icon-award"/></svg>
        <!-- <b>{{ paper.award }}</b> -->
        </span>
      {% endif %}
  	  {% if paper.important %}
  	    <span style="color: red">&#9733;</span>
  	  {% endif %}
  	  {% if paper.acc_rate %}
  	  	<a href="{{ paper.url }}"> {{ paper.title }} </a> ({{ paper.acc_rate}}% Acceptance Rate) <br>
  	  {% else %}
      	<a href="{{ paper.url }}"> {{ paper.title }} </a> <br>
      {% endif %}
      {{ paper.authors }} <br>
      {% if paper.venue_abb %}
         <em>{{ paper.venue }} ({{ paper.venue_abb }})</em>   
      {% else %}
      	 <em>{{ paper.venue }}</em>   
      {% endif %}
     {% if paper.abstract %}
     <details>
      <summary>Abstract</summary>
  		{{ paper.abstract }}    
     </details>
     {% endif %}

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
      {% if paper.link %}
      <a href="{{ paper.link }}" target="_blank">
        <span class="icon"><svg><use xlink:href="#icon-link"/></svg></span>
      </a>
      {% endif %}
      {% if paper.poster %}
      <a href="{{ "/resources/posters/" | append: paper.poster | append: ".pdf" | prepend: site.baseurl }}" target="_blank">
        <span class="icon"><svg><use xlink:href="#icon-pdf"/></svg></span>
      </a>
      {% endif %}
    </div>
  </div>
  {% endfor %}
{% endfor %}