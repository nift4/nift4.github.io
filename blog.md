---
---
# Blog
{% for post in site.posts %}{{ post.excerpt }}<a href="{{ post.url }}">Read more...</a>{% endfor %}
