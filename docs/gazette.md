---
layout: default
title: GridScout Gazette™
permalink: /gazette/
redirect_from:
  - /blog/
  - /journal/
---

# GridScout Gazette™ <a class="btn" href="{{ '/feed.xml' | prepend: site.url }}">Subscribe</a>
Here's what's going on in the manly arts, from the [GridScout™][gridscout] team.


{% for post in site.posts %}
<div class="post" markdown="1">
# [{{ post.title }}]({{ post.url }})
<div class="post-metadata">{{ post.date | date: "%Y-%m-%d" }} — by {{ post.author }}</div>
{{ post.content }}
<div class="post-metadata">© {{ post.date | date: "%Y" }} {{ post.author }} &amp; gridscout.net </div>
</div>
{% endfor %}

<a class="btn" href="{{ '/feed.xml' | prepend: site.url }}">Subscribe</a>


[gridscout]: /
