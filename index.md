---
layout: home
title: "Welcome to My Blog"
---

# Welcome! 👋
Hi. I am Vanilla20. This page is dedicated to sharing my experience in Cybersecurity with various categories I have explored.

## Categories

🔎 **[OSINT](../categories/OSINT/)** - Articles about OSINT challenges and techniques I used.

## Recent Posts
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      - <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>