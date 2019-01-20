---
layout: default
short_name: nardiena
name: Nardiéna Althafia Pratama
position: Ketua 1
permalink: /nardiena/
---
Welcome to my page!
-----

Hello! I'm <h1>{{ page.full_name }}</h1>. You can call me Nardién(a).


So, this break, I've been working on a project for one of my Computer Science courses, Operating Systems. My role is the <h2>{{ page.position }}</h2> If you're interested, feel free to check it out the links below!

[Nardiéna's Project](https://nardienapratama.github.io/extra182/)
[Personal GitHub Pages Website](https://nardienapratama.github.io/extra182)

<h1> My Latest Posts</h1>
<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.short_name %}
  {% for post in filtered_posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>
