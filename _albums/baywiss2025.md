---
title: "BayWiss Prize 2025"
collection: albums
date: 2025-10-17
cover: /assets/photos/BayWISS2025/cover.jpeg
photos_path: /assets/photos/BayWISS2025
---

Receiving the **BayWiss Prize 2025** in Bavaria, Germany.

---

<!-- 小图照片墙 -->
<div class="album-gallery">
{% assign prefix = page.photos_path %}
{% for file in site.static_files %}
{% if file.path contains prefix and file.extname != ".md" and file.name != "cover.jpg" %}
<figure class="album-gallery-item">
<a href="{{ file.path | relative_url }}">
<img src="{{ file.path | relative_url }}" alt="{{ page.title }} photo" loading="lazy">
</a>
</figure>
{% endif %}
{% endfor %}
</div>
