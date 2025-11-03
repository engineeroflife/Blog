---
layout: default
title: "True Place Gifts Blog"
---

<h1>{{ page.title }}</h1>

<p>Welcome to the True Place Gifts blog! ✨  
Here we share stories behind our products and the people who make them.</p>

<hr>

<h2>Latest Posts</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
