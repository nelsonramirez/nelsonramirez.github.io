---
layout:          page
title:           Projects*
show_collection: projects
featured:        true
---

{% for project in site.projects %}
  {% include project-card.html project=project %}
{% endfor %}
