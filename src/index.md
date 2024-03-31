---
title: Main Page
search:
  exclude: true
---

{% include 'index_body' %}

## Navigation

{% assign navigation_full = 'site.src.navigation.md' | split: '---' %}
{% assign navigation_without_header = navigation_full[2] %}
{{ navigation_without_header }}
