---
layout: page
title: Artillery Sim
description: Paris gun performance analysis via RK4 on a Rayleigh distribution + FCTS heat scheme
img: assets/img/ParisGun.png
importance: 4
category: Undergraduate
---
The paris gun was a large weapon used during WW1 that was used for long range bombings. We present a detailed analysis of its accuracy and firing rate using a Rayleigh distribution and a forward time-centered space heat scheme.

## GitHub Repository

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% if repo == "russburns/Paris_Cannon_Model" %}
      {% include repository/repo.liquid repository=repo %}
    {% endif %}
  {% endfor %}
</div>
{% endif %}