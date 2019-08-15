---
---
# Blog
{% for post in site.posts %}{{ post.excerpt }}<a href="{{ post.url }}">{{ post.excerpt }}</a>{% endfor %}
