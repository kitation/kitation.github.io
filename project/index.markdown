---
layout: page
status: publish
published: true
title: Games Research
author:
  display_name: chad
  login: chad
  email: katayoku@googlemail.com
  url: ''
---

<div class="home">

<p>
For my master's dissertation I did a research project into uncomfortable digital game experiences. This page contains a serialisation of that paper, rewritten to make it more readable. The full academic paper (20k words) is available to <a href="https://drive.google.com/file/d/1EF5IQUuKoYJLtt3hJ5nycPdaQ6RHGzJd/view?usp=sharing">download from Google Drive here</a>.
</p>

<h2>Abstract</h2>
<p>
This project looks at the player experience around discomfort. While there is an increasing amount of research in the player experience area, little work has been done specifically around discomfort in digital games and what this means. Two studies look at the experience, causes and motivations behind the play of games that induce discomfort. An analysis of Steam reviews suggests that character loss, toxic playerbases and mismatched expectations play some role in uncomfortable experiences. A follow-up questionnaire study focused on asking participants about uncomfortable experiences in Darkest Dungeon, Papers Please and Fallout 4, where the findings suggest that empathy, reflection, pressure, moral choices and exposure to uncomfortable topics can create different forms of discomfort. The contributions of this paper are 1) a greater understanding of uncomfortable experiences in digital games 2) an evaluation of the usefulness of online reviews in this field of research and 3) suggestions for future work in this area.
</p>

<h2>Posts</h2>

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
