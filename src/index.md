---
title: Main Page
search:
  exclude: true
---

{% include 'index_body' %}

## Navigation

{% assign navigation_full = site.src.navigation | split: '---' %}
{% assign navigation_without_header = include_content[2] %}
{{ navigation_without_header }}

