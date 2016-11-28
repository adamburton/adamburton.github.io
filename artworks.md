---
layout: page
title: Artworks
homepage: yes
short-description: "&nbsp;"
---

hen I was at art school I was into paper, words, and printing. I had decided that art galleries are a barrier that keeps people away from art—in the sense that you have to go into them to look at the work. The barrier creates problems for different people in different ways. I wanted my work to be outside of those rooms and I wanted to remove the barrier.

I made a magazine for a while and asked friends to make drawings or writing for it. I left copies of the magazine on benches in parks. I enjoy this kind of distribution—it feels democratic. It helped me to think about disseminating information. I also made posters that covered walls with a lot of nonsense writing. And I made web sites.

After university I went back to university. I had planned to keep making the magazine but one day I started to read a book of William Morris' political writing and it split my skull open. I was learning to print letterpress and I needed words to print. In my head and in my notebooks political ideas, an understanding of socialism and anarchism, were forming. I used some of what I had written down to make some posters. I wanted to paste them up in the street but I was scared so I showed them to people in an art gallery.

Then I moved to London. I was feeling very worried about climate change and I made some notices about what I thought might happen. I was also thinking about caring for other people in the world and for future generations and I made some work about it that tried to make a gallery more open.

For another I printed a pamphlet. It was about Haiti. But it stayed in the gallery. I gave up trying to distribute the magazine.

Someone asked me to make a big exhibition and I was thinking about social movements. I made a colourful exhibition about different ways that people try to change the world. The gallery was a thoroughfare and there were lots of leaflets for people to take away. It felt good but not quite right.

I had been trying to make a newspaper about British foreign policy but it was awful. I did make one issue and handed it out at train stations near where I live. A documentary by John Pilger called Stealing A Nation helped me to concentrate. It is about the people of the Chagos Islands. I made a pamphlet about what happened to them and I handed it out on the street. Later I organised some screenings of the documentary.

In Penzance I made another pamphlet about Haiti and I posted 2,000 copies of it through 2,000 front doors. Some people came to the gallery to talk about it. Again, it felt good but not quite right.

I was reading a lot about education and I tried to organise some meetings and discussions about it but I did not do it properly. I tried to learn from it though. I learn from my mistakes too slowly.

A friend asked me to make an exhibition in her bookshop and I had been reading a lot of Noam Chomsky. I made some printed letterpress posters of things that he has quoted of other people. I sold them to raise money for an Anarchist bookshop.

This was kind of the last of it.
Other things happened.

*****

<div>
{% for artwork in site.artworks %}
	 <a href="{{ artwork.url }}">{{ artwork.title }}</a> &nbsp; {{ artwork.year }}
       <p class="text-muted">{{ artwork.short-description }}</p>
{% endfor %}
</div>
