---
---
# Home
Hello. :)
## About
I'm nift4 (a little bit privacy aware, I don't even share my real name) and this website is because I wanted a blog and a hosting solution for some other things.
## Blog
<div id="posts">
  {% for post in site.posts %}
      <a href="{{ post.url }}"><p>{{ post.excerpt }}</p></a>
  {% endfor %}
</div>
