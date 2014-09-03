---
layout: page
title: Archive
permalink: /archive/
---

{% for post in site.posts %}
  * {{ post.date | date: "%b %e, %Y" }} - [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}