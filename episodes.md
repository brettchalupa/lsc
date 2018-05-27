---
layout: page
title: Episodes
description: "List of Lunar Space Colony episodes in chronological order."
permalink: /episodes
---

{%- if site.posts.size > 0 -%}
  <ul class="post-list">
    {%- for post in site.posts reversed -%}
    <li class="post-list-item">
      <a class="post-link" href="{{ post.url | relative_url }}">
        <img class="post-list-item--image" src="{{ post.image }}" alt="{{ post.title | escape }} Thumbnail">

        <h2 class="post-list-item--title">
          {{ post.title | escape }}
        </h2>
      </a>
    </li>
    {%- endfor -%}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></p>
{%- endif -%}
