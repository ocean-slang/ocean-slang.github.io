---
layout: page
title: GO-SWACE
description:
img: assets/img/Edward.png
importance: 3
category: work
---

Project goal: The observed phytoplankton response to mesoscale eddies, measured from satellite altimetry and chlorophyll-a concentration, often lacks consistency. We hypothesize that this is because eddy structures vary spatially and temporally and drive shifts in phytoplankton communities that chlorophyll-a estimates cannot fully capture. Disentangling these processes requires fine-scale tracking of both eddy dynamics and phytoplankton communities. Our objective is to leverage velocities derived from SWOT, observed at scales (O(1 km)) finer than those of previous satellite altimeters, phytoplankton community distributions from PACE, and depth-resolved observations from Argo floats to reveal the impacts of these mechanisms on observed phytoplanktonic ecosystems.

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}

<embed src="https://web.uri.edu/gso/news/mapping-ocean-ecosystems-with-nasa-technology-at-pace-hackweek/" style="width:800px; height: 1000px;">
