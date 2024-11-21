---
layout: page
title: OTKB Code
description: Enabled operation of optical tweezers 
img: assets/img/OpticalTweezers.jpg
importance: 4
category: Undergraduate
---
I assisted with code development for Zachary Lutzky's (W&M '24) senior thesis. My 400 lines allowed him to interface with and characterize a [Thorlabs OTKB/M](https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_ID=3959), which is now William & Mary's only operational set of Optical Tweezers.

## GitHub Repository

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% if repo == "russburns/Zach_Thesis" %}
      {% include repository/repo.liquid repository=repo %}
    {% endif %}
  {% endfor %}
</div>
{% endif %}