---
layout: default
title: Travel
permalink: /travel/
---
<section class="page-section">
  <h2>Travel</h2>
  <p>Travel has shaped how I see community and creativity. Use the Travel Posts in the CMS to add stories with images.</p>

  <h3>Latest Posts</h3>
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <small>— {{ post.date | date: "%b %d, %Y" }}</small>
      </li>
    {% endfor %}
  </ul>
</section>

