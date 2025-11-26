---
layout: single
title: "Photos"
permalink: /photos/
author_profile: true
---

Here are some photo albums from conferences, awards, and lab life.

---

{% assign albums = site.albums | sort: "date" | reverse %}

<div class="album-list">
{% for album in albums %}
  <a class="album-card" href="{{ album.url | relative_url }}">
    <div class="album-cover">
      {% if album.cover %}
        <img src="{{ album.cover | relative_url }}" alt="{{ album.title }} cover" loading="lazy">
      {% endif %}
    </div>
    <div class="album-info">
      <h3>{{ album.title }}</h3>
      {% if album.date %}
        <p class="album-date">{{ album.date | date: "%B %Y" }}</p>
      {% endif %}
    </div>
  </a>
{% endfor %}
</div>
