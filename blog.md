---
layout: page
permalink: /blog/
title: blog
description: An infrequently updated blog.
---

<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <h2><a class="project-title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: '%B %-d, %Y — %H:%M' }}</p>
        <p>{{ post.description }}</p>
        <hr/>
      </li>
    {% endfor %}
</ul>