---
layout: page
title: Fermilab Neutrino Data Analysis
description: Fermilab Neutrino Data Analysis
img: assets/img/Fermilab.png
importance: 2
category: Undergraduate
---
An analysis of the behavior of neutrino energy from a 1,339 entry Fermilab experiment against a Monte-Carlo simulation. The two-flavor oscillation approximation is used to draw statistical conclusions about the mixing angle and change in sample mass.

## GitHub Repository

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% if repo == "russburns/Fermilab_Neutrino_Statistics" %}
      {% include repository/repo.liquid repository=repo %}
    {% endif %}
  {% endfor %}
</div>
{% endif %}