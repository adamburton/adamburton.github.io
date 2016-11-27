---
layout: page
title: Music
homepage: yes
short-description: "&nbsp;"
---

I make music with two friends, Ben and Lee, in a band named *White Tantrum*. We started off as a sort of rubbish-punk outfit and for quite a while we have been a bad-noise duo because Lee lives in a different city. Recently Lee has been visiting more and we are trying to get organised. Mostly we make bad-noise.

I am going to post some of our numbers here and maybe try to explain what is going on. A lot of the music that we make is embarrassing but really good at the same time. It is un-listenable.

We have been playing together for about ten years and we have only performed live twice. If you like our music please book us for a gig.

*****

<div>
{% for music in site.music %}
	 <a href="{{ music.url }}">{{ music.title }}</a>
      <p class="text-muted">{{ music.short-description }}</p>
{% endfor %}
</div>