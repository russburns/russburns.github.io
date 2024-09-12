---
layout: page
title: Solar System EOM
description: Group project
img: assets/img/SolarEOM.jpg
importance: 3
category: Undergraduate
---
{% for repo in site.data.repositories.github_repos %}
  {% if repo.name == "Solar_System_EOM" %}
    {% include repository/repo.liquid repository=repo %}
  {% endif %}
{% endfor %}



A Julia implementation of [Successive Convexification for 6-DoF Mars Rocket Powered Landing with Free-Final-Time](https://arxiv.org/pdf/1802.03827.pdf) by Miki Szmuk and Behçet Açikmeşe. The animation on the left is a planar trajectory and the animation on the right is a recreation of SpaceX's Starship flip maneuver. My code for this project can be found [here](https://github.com/govindchari/PTR). Some notes I wrote on PTR can be found [here](/assets/pdf/PTR%20Walkthrough.pdf)

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% if repo.name == "Solar_System_EOM" %}
      {% include repository/repo.liquid repository=repo %}
    {% endif %}
  {% endfor %}
</div>
{% endif %}

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
