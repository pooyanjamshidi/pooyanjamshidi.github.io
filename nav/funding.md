---
layout: default
title: Funding
permalink: /funding/
weight: 7
group: funding
---
AISys receives funding from several sources.
{% for funding in site.data.funding %}
<div class="row" name="{{ funding.id }}">
  <div class="row-pic">
		{% include /functions/getfundingpic.html funding=funding %}
	</div>
	<div class="row-info">
    <a href="{{ funding.website | default: "#" }}" target="_blank">{{ funding.name }}</a>
		<p>
      {{ funding.description }}
    </p>
	</div>
</div>
{% endfor %}
