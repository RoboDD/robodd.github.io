---
layout: page
title: projects-test
permalink: /projects-test/
description: A growing collection of your cool projects.
nav: true
nav_order: 2
display_categories: [work, fun]
horizontal: false
---

<!-- pages/projects.md -->
<div class="portfolio">
{%- if site.enable_portfolio_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_portfolio = site.portfolio | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for portfolio in sorted_portfolio -%}
      {% include portfolio_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for portfolio in sorted_portfolio -%}
      {% include portfolio.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_portfolio = site.portfolio | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for portfolio in sorted_portfolio -%}
      {% include portfolio_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for portfolio in sorted_portfolio -%}
      {% include portfolio.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
