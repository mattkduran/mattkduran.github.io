---
title: ~/Matt's Blog
layout: home
permalink: /
---

# A blog for weird, interesting things

Hi there! This blog acts as both a portfolio for projects that I'm working on as well as a place to store articles or instructions for things.

<ul>
  {% for post in site.posts %}
      <li>
            <a href="{{ post.url  }}">{{ post.title  }}</a>
      </li>
    {% endfor %}
</ul>
