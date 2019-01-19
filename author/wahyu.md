---
layout: default
short_name: wadt
name: Wahyu Ananda Duli Tokan
position: Ketua 3
permalink: /wahyu/
---


Herzlich Willkommen !!
---

Hello !!

My name is <h1>{{ page.full_name }}</h1>, i am a Computer Science Student at University of Indonesia

In this project,my role is <h2>{{ page.position }}</h2> and i made a GitHub pages and make it to run locally by Local jekyll

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


