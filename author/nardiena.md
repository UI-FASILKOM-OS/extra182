---
layout: default
short_name: nardiena
full_name: Nardiéna Althafia Pratama
position: Ketua 1
permalink: /nardiena/
---
Welcome to my page!
-----

Hello! I'm {{ page.full_name }}. You can call me {{ page.short_name }}.


So, this break, I've been working on a project for one of my Computer Science courses, Operating Systems. My role is the {{ page.position }}. If you're interested, feel free to check it out the links below!

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
