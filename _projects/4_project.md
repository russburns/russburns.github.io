---
layout: page
title: Kaleidomnene
description: Robotic kaleidoscope project
img: assets/img/KaleidoGUI.jpg
importance: 3
category: Undergraduate
---
We developed and pitched a super coll robotic kaleidoscope product as part of an embedded controllers class. Manual and comprehensive documentation are available on Github.

## GitHub Repository

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% if repo == "russburns/KaleidoMnene" %}
      {% include repository/repo.liquid repository=repo %}
    {% endif %}
  {% endfor %}
</div>
{% endif %}