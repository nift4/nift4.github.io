---
---
# Home
Hello. :) I'm testing github.io's JekyllRB...
## Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}"><p>{{ post.excerpt }}</p></a>
    </li>
  {% endfor %}
</ul>
