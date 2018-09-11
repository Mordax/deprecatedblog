---
layout: page
title: Vacuum Tube
tagline: A series of technical ramblings that occasionally overheat
---
{% include JB/setup %}

I'm so bad at knowing what sort of tone I want to set with my online persona. Everytime I see my old introductions, they're
always so embarrassing. 

Anyways, welcome to my blog. I hope you'll find useful information and fixes for broken technology. 

I have pretty strong copyleftist sentiments, a willingness to accept our robot overlords, am a giant history nerd, hoard too many
books and love to learn. 

## Recent Posts

---
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
---


