---
layout: default
short_name: farz
full_name: Fadhriz Q. A.
position: Ketua2
permalink: /farz/
---
Hello, my name is
<h1>{{ page.full_name }}</h1>

My position is
<h2>{{ page.position }}</h2>

<h1>Latest Posts</h1>

<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.short_name %}
  {% for post in filtered_posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>
