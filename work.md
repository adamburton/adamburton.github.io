---
layout: page
title: Work
homepage: yes
short-description: "&nbsp;"
order: 1
---

Some of the time I do some political organising or support work. Not much, not enough. 

*****

<div>
{% for work in site.work %}
	 <a href="{{ work.url }}">{{ work.title }}</a>
      <p class="text-muted">{{ work.short-description }}</p>
{% endfor %}
</div>
