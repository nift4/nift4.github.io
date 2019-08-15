---
---
# Blog
{% for post in site.posts %}
<a href="{{ post.url }}"><p>{{ post.excerpt | markdownify }}</p></a>
{% endfor %}
