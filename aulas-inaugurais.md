---
layout: default
title: Aulas Inaugurais
permalink: /aulas-inaugurais/
---

<h2>Fotos das Aulas inaugurais</h2>

{% for post in site.posts %}
  <div class="inaugural-class-container">
    <a href="{{ post.url | prepend: site.baseurl }}">
      <h3>{{ post.title }}</h3>
    </a>
  </div>
{% endfor %}
