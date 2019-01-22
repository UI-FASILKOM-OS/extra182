---
layout: default
short_name: wahyu
full_name: Wahyu Ananda Duli Tokan
position: Ketua 3
permalink: /wahyu/
---


Herzlich Willkommen !!
---

Hello !!

My name is {{ page.full_name }}, i am a Computer Science Student at University of Indonesia

In this project,my role is {{ page.position }} and i made a GitHub pages and make it to run locally by Local jekyll

You can find my GitHub pages, my personal website, and my logs here

- [GitHub Pages](https://wahyuadt.github.io/extra182)
- [Personal WebSite](https://tumpeng1.herokuapp.com)  

<h1>Latest Posts</h1>
<ul>
  {% assign filtered_posts = site.posts | where: 'author', page.short_name %}
  {% for post in filtered_posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</ul>


