---
title: About
layout: page
---
![Profile Image]({% if site.external-image %}{{ site.picture-about }}{% else %}{{ site.url }}/{{ site.picture-about }}{% endif %})

UI/UX designer from Saint-Petersburg

I create mobile interfaces at [E-Legion](https://www.e-legion.com)

<h2>Portfolio</h2>
<ul>
    {% for project in site.projects-list %}
		<li><a href="{{ project.link }}">{{ project.title }}</a></li>
    {% endfor %}
</ul>