---
layout: default
title: Blog — Jorge de la Flor
---

# Blog

Artículos sobre arquitectura de software, diseño de protocolos, sistemas embebidos, Python, Rust y reflexiones técnicas.

{% assign posts = site.posts | sort: 'date' | reverse %}
{% if posts.size == 0 %}
  <p style="color: var(--text-muted);">Próximamente nuevos artículos. ¡Vuelve pronto!</p>
{% else %}
  {% for post in posts %}
  <div style="border-bottom: 1px solid var(--border-color); padding: 1.5rem 0;">
    <h3 style="margin-bottom: 0.2rem;">
      <a href="{{ post.url | relative_url }}" style="color: var(--text-primary);">{{ post.title }}</a>
    </h3>
    <p style="color: var(--text-muted); font-size: 0.85rem;">
      {{ post.date | date: "%d/%m/%Y" }} · 
      {% for category in post.categories %}
        <span style="background: var(--bg-secondary); padding: 0.1rem 0.5rem; border-radius: 10px; border: 1px solid var(--border-color); font-size: 0.75rem;">{{ category }}</span>
      {% endfor %}
    </p>
    <p style="color: var(--text-secondary);">{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    <a href="{{ post.url | relative_url }}" class="cta-link">Leer más →</a>
  </div>
  {% endfor %}
{% endif %}

[← Volver al inicio]({{ '/' | relative_url }})