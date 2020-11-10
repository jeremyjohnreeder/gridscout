---
layout: default
title: GridScout Gazette™
permalink: /gazette/
redirect_from:
  - /blog/
  - /journal/
---

# GridScout Gazette™ <a class="btn" href="{{ '/feed.xml' | prepend: site.url }}">Subscribe</a>
Here's what's going on in the manly arts, from the GridScout™ team.


{% for post in site.posts limit:3 %}
<div class="post" markdown="1">
# [{{ post.title }}]({{ post.url }})
<div class="post-metadata">{{ post.date | date: "%Y-%m-%d" }} — by {{ post.author }}</div>
<div class="post">{{ post.content }}</div>
<a class="btn" href="https://dissenter.com/discussion/begin?url={{ post.url | prepend: site.url }}">Comment</a>
<span class="post-metadata">
	© {{ post.date | date: "%Y" }} {{ post.author }} &amp; gridscout.net
</span>
</div>
{% endfor %}
{% for post in site.posts offset:3 %}
<div class="post" markdown="1">
# [{{ post.title }}]({{ post.url }})
<div class="post-metadata">{{ post.date | date: "%Y-%m-%d" }} — by {{ post.author }}</div>
<div class="post">{{ post.excerpt | truncatewords:9 }} <a href="{{ post.url }}">(more)</a></div>
</div>
{% endfor %}

<a class="btn" href="{{ '/feed.xml' | prepend: site.url }}">Subscribe</a>
