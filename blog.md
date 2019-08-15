---
---
# Blog
{% for post in site.posts %}
      <a href="{{ post.url }}">
      <p>{{ post.excerpt }}</p>
      </a>
{% endfor %}
