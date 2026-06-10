---
layout: page
title: FLOW Lab News
subtitle: Updates from the FLOW Lab
hero_image: /img/hero-banner.jpg
permalink: /news.html
show_sidebar: false
---

{% assign news_posts = site.posts %}

{% for post in news_posts %}
<article class="box">
  <h2 class="title is-4">
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </h2>

  <p class="subtitle is-6">
    {{ post.date | date: "%-d %B %Y" }}
  </p>

  <div class="content">
    {{ post.excerpt }}
  </div>

  <p>
    <a class="button is-small is-link" href="{{ post.url | relative_url }}">
      Read more
    </a>
  </p>
</article>
{% endfor %}