---
layout: home
title: Home
---

<div id="intro-wrapper" class="l-text">
	<div id="intro-title-wrapper">
		<div id="intro-image-wrapper">
			<img id="intro-image" src="/images/portrait.jpg"></div>
		<div id="intro-title-text-wrapper">
			<h1 id="intro-title">Hi, I'm Qianyu Zheng</h1>
			<div id="intro-subtitle">I'm a Master's Student and Graduate Researcher at Georgia Tech.</div>
			<div id="intro-title-socials">
				{% for link in site.data.social-links %}
					{% if link.on-homepage == true %}
						{% include social-link.html link=link %}
					{% endif %}
				{% endfor %}
			</div>
		</div>
	</div>
	<div id="everything-else" class="l-middle">
		<a href="{{ site.url }}/cv"><div><i class="fa fa-portrait icon icon-right-space"></i>CV</div></a>
		<a href="{{ site.url }}/projects"><div><i class="fa fa-shapes icon icon-right-space"></i>Projects</div></a>
		<a href="{{ site.url }}/everything-else"><div><i class="fa fa-list-ul icon icon-right-space"></i>Everything Else</div></a>
	</div>
	<div>
		Welcome to my personal website! I am a Master's student in <b>Computer Science</b> at the Georgia Institute of Technology, where I also earned my B.S. in Computer Science with a perfect 4.0 GPA. I build machine learning systems for scientific problems, with a working foundation in Python, PyTorch, big data tooling, and cloud computing.
	</div>
	<div style="height: 1rem"></div>
	<div>
		As a researcher, I work on <b>AI for science</b> in the <a href="https://www.fung-group.org/">Fung Group</a> at Georgia Tech, advised by Assistant Professor <a href="https://cse.gatech.edu/people/victor-fung">Victor Fung</a>. My research covers <b>machine learning interatomic potentials</b> — making them physically reliable enough for molecular dynamics — and <b>LLM agent systems</b> that edit crystal structures from natural language and search for new materials by inverse design. This work has produced first-author papers in the <i>Journal of Chemical Information and Modeling</i> and the <i>Journal of Renewable and Sustainable Energy</i>.
	</div>
	<div style="height: 1rem"></div>
	<div>
		Most recently I was a machine learning intern at <a href="https://www.lila.ai/">Lila Sciences</a> in Cambridge, MA, building agentic frameworks for automated model development. Before that I spent a semester at the <a href="https://www.iwes.fraunhofer.de/en.html">Fraunhofer Institute for Wind Energy Systems</a> in Bremen, Germany, turning a year of terabyte-scale, multi-instrument wind measurements into a validated benchmark dataset for wake model evaluation.
	</div>
	<div style="height: 1rem"></div>
	<div>
		My <a href="/CV/PhD_application_CV.pdf">academic CV</a> and <a href="/CV/Qianyu%20Zheng%20-%20Resume.pdf">resume</a> are available as PDFs.
	</div>
	<div style="height: 1rem"></div>
</div>

<hr class="l-middle home-hr">
