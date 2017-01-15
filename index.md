---
layout: page
title: Life in Binary
tagline: A series of occasionally technical ramblings
---
{% include JB/setup %}

Welcome to my blog. It's my first attempt at being one of those cool tech wizards who sometimes impart invaluable 
knowledge unto others. 

I'm obviously off to a great start. 

(Warning, there will be weird sarcasm and strange jokes in this blog. `Turn back before it's too late!`)

## Recent Posts

---
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
---

Alongside Technical related postings, I am a Copyleftist, a Transhumanist, an avid reader and an Eastern culture enthusiast.

`Blog in Progress, I repeat, Blog in Progress!`



