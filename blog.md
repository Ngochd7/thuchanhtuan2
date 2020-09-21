---
layout: page
title: Blog
permalink: /blog/
---
<h1>Bài viết của mình: </h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="/thuchanhtuan2{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
