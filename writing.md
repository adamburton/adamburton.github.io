---
layout: page
title: Writing
homepage: yes
short-description: "&nbsp;"
order: 2
---

A few years ago I decided that I wanted to do writing. I applied for some commissions and some friends asked me to write things for them. Some of what I wrote was published in print.

I stopped trying to write because I find it difficult. But I am going to try again.

*****

<div>
{% for writing in site.writing %}
	 <span class="collection-link"><a href="{{ writing.url }}">{{ writing.title }}</a> &nbsp; {{ writing.year }}</span>
      <p class="text-muted">{{ writing.short-description }}</p>
{% endfor %}
</div>
