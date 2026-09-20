---
layout: page
title: Projects
permalink: projects/
---

Research systems and side projects I have built, plus the occasional hackathon.

## Publications

Peer-reviewed research, both as first author.

<div class="project-spacer-small"></div>

{% for pub in site.data.publications %}
{% include cv/publication.html pub=pub %}
{% endfor %}

<div class="project-spacer"></div>

## Long-term Projects

<div class="project-spacer-small"></div>

<div class="cover-wrapper cover-wrapper-2-col l-middle">
	{% for feature in site.data.designs %}
		{% if feature.featured == true %}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
</div>

<div class="project-spacer"></div>

## Hackathon Projects

Projects completed for Hackathons.

<div class="cover-wrapper cover-wrapper-2-col l-middle">
	{% for feature in site.data.personal_projects %}
		{% if feature.featured == true %}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
</div>
