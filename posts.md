---
layout: bright
title: What's up!
permalink: /posts/
---

Here lives the posts made by Yusuf Fadairo!

{% for post in site.posts %}
  <h3 class="link"><a class="link gray" href="{{ post.url }}">{{ post.title }}</a></h3>
  <p class="date">
    <span class="date">{{ post.date | date_to_long_string }}</span>
  </p>
{% endfor %}