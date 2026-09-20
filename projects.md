---
layout: page
title: Projects
permalink: projects/
---

Things I do, including research, academic course projects, and miscellaneous interests.

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
