---
layout: page
status: publish
published: true
title: Project
author:
  display_name: chad
  login: chad
  email: katayoku@googlemail.com
  url: ''
---

<div class="home">

 {% for post in site.categories.project %}
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p class="author">
    <span class="date">{{ post.date | date: "%a %b %d, %Y" }}</span>
  </p>
  <div class="content">
    {{ post.excerpt }}
  </div>
{% endfor %}
</div>
