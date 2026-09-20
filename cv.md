---
layout: cv
title: CV
permalink: cv/
---

<h1 id="cv-title"><a href="{{ site.url }}">Qianyu Zheng</a></h1>

<p id="cv-subtitle"><i>Master's Student, Graduate Researcher (<span class="cv-ai">AI for Science</span>)</i></p>

<div>
I work on <b>machine learning for scientific discovery</b>: machine learning interatomic potentials, LLM agents for materials design, and the data pipelines that make scientific measurements usable. My current research combines physics-informed modeling, <b>agentic systems</b>, and high performance computing to answer scientific questions and accelerate materials discovery.
</div>

<div class="cv-spacer"></div>

<div>
<b>Research interests:</b> AI for science, machine learning interatomic potentials, large language model agents, inverse design of materials, molecular dynamics simulation, data science.
</div>

<div class="cv-spacer"></div>

<div>
During my studies and internships, I have collaborated with researchers, scholars, and developers at Georgia Tech <img class="intro-logo" style="width: 24px;" src="/images/Georgia_Tech_logo.svg">, Lila Sciences, the Leibniz Institute of Plant Biochemistry <img class="intro-logo" style="width: 24px;" src="/images/ipb_logo.svg">, and Fraunhofer IWES <img class="intro-logo" style="width: 24px;" src="/images/fraunhofer_gesellschaft_logo.svg">.
</div>

<div class="cv-spacer"></div>

<div class="cv-image-links-wrapper">
	<div class="cv-image-links">
		{% for link in site.data.social-links %}
			{% if link.cv-group == 1 %}
				{% include cv-social-link.html link=link %}
			{% endif %}
		{% endfor %}
	</div>
	<div class="cv-image-links">
		{% for link in site.data.social-links %}
			{% if link.cv-group == 2 %}
				{% include cv-social-link.html link=link %}
			{% endif %}
		{% endfor %}
	</div>
</div>

***

## Education

{::nomarkdown}
{% for degree in site.data.education %}
{% include cv/degree.html degree=degree %}
{% endfor %}
{:/}

## Publications

{% for pub in site.data.publications %}
{% include cv/publication.html pub=pub %}
{% endfor %}

## Industry Research Experience

{% for experience in site.data.experiences %}
{% if experience.type == 'industry' %}
{% include cv/experience.html experience=experience %}
{% endif %}
{% endfor %}

## Academic Research Experience

{% for experience in site.data.experiences %}
{% if experience.type == 'academic' %}
{% include cv/experience.html experience=experience %}
{% endif %}
{% endfor %}

## Projects

{% for design in site.data.designs %}
{% include cv/design.html design=design %}
{% endfor %}

{% for design in site.data.personal_projects %}
{% include cv/design.html design=design %}
{% endfor %}

## Teaching

{% for teach in site.data.teaching %}
{% include cv/teaching.html teach=teach %}
{% endfor %}

## Honors and Awards

{% for award in site.data.awards %}
{% include cv/award.html award=award %}
{% endfor %}

## Certificates

{% for certificate in site.data.certificates %}
{% include cv/certificate.html certificate=certificate %}
{% endfor %}

## Technical Skills

{% for skill in site.data.skills %}
{% include cv/skill.html skill=skill %}
{% endfor %}
