---
layout: default
---

{% for post in site.posts %}
# [{{ post.title }}]({{ post.url | absolute_url }})
*{{ page.tags | array_to_sentence_string }}*

{{ post.excerpt }}

---

{% endfor %}