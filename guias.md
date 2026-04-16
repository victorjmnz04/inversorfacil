---
layout: default
title: Guías
description: Guías para empezar a invertir en España desde cero, sin conocimientos previos.
---

<div class="container" style="padding-top: 40px;">

  <div class="post-header" style="margin-bottom: 32px;">
    <span class="post-category">Guías</span>
    <h1 style="font-size: 2rem; font-weight: 700; margin: 12px 0 8px;">Guías para invertir desde cero</h1>
    <p style="color: var(--texto-suave);">Todo lo que necesitas saber para empezar a invertir en España, explicado sin tecnicismos.</p>
  </div>

  <div class="posts-grid">
    {% for post in site.posts %}
    <a href="{{ post.url | relative_url }}" class="post-card">
      <span class="post-card-category">Guía</span>
      <h3>{{ post.title }}</h3>
      <p>{{ post.description }}</p>
      <span class="read-more">Leer más →</span>
    </a>
    {% endfor %}
  </div>

</div>