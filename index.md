---
title: <a href="https://nift4.org">nift4</a>
---
# Home
Hello. :)
## Blog
<div id="posts">
  {% for post in site.posts %}
      <a href="{{ post.url }}"><p>{{ post.excerpt }}</p></a>
  {% endfor %}
</div>
