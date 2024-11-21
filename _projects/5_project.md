---
layout: page
title: Solar System EOM
description: Code to plot solar system celestial body trajectories
img: assets/img/SolarEOM.jpg
importance: 3
category: Undergraduate
---
Project that solves the 3D equations of motion for the solar system via 2nd order ODES and plots their orbits. It's useful for predictive analysis of different parts of the system. Initial conditions were pulled for 2022-Nov-03, 00:00:00.0000 UTC from the HORIZONS web app.

{% include figure.liquid loading="eager" path="assets/img/earthmars.png" title="example image" class="img-fluid rounded z-depth-1" %}

## GitHub Repository

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% if repo == "russburns/Solar_System_EOM" %}
      {% include repository/repo.liquid repository=repo %}
    {% endif %}
  {% endfor %}
</div>
{% endif %}

