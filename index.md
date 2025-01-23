---
layout: home
title: "Accueil"
permalink: /
---

<p style="text-align: right;">
  <img src="./assets/images/logo-UT2J.jpg" alt="Logo UT2J" >
</p>

# Bienvenue sur {{ site.title }}

## Pages disponibles :

<ul>
  {% for page in site.pages %}
    {% if page.title and page.permalink != '/' %}
      <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>

## Articles de blog récents :

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span> - Publié le {{ post.date | date: "%d %B %Y" }}</span>
    </li>
  {% endfor %}
</ul>
