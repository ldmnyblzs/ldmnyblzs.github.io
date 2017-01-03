---
layout: default
---

{% for post in site.posts %}
# [{{ post.url | absolute_url }}]({{ post.title }})

{{ post.excerpt }}

{% endfor %}