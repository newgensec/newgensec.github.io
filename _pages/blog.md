---
layout: default
title: KRL Research Group - Blog
permalink: /blog/
---
<h1 class="sapienza-text">Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
       <h5 style="font-weight:bold;">{{post.display_date}}</h5>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>