---
---
# Blog
{% for post in site.posts %}<a href="{{ post.url }}">{{ post.excerpt }}</a>{% endfor %}
