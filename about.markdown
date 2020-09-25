---
layout: page
title: Blog 
permalink: /Blog/
---
<h1>Bài mới</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="/Wepxin{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
