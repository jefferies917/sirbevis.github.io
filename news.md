---
layout: default
title: News
permalink: /news/
description: Latest news and updates from Sir Bevis Lodge.
hero_image: /assets/images/lodge.jpg
hero_alt: Our Lodge Hall
---

# News

{% for post in site.posts %}
  <article class="news-item">

    <h2 class="news-title">
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </h2>

    <p class="news-meta">
      {{ post.date | date: "%d %B %Y" }}
    </p>

    <div class="news-excerpt">
      {{ post.excerpt }}
    </div>

    <p>
        <a href="{{ post.url | relative_url }}">Read more →</a>
    </p>

  </article>
{% endfor %}

