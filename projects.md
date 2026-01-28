---
layout:          page
title:           Mes Projets
show_collection: projects
featured:        true
---

<p class="projects-intro">
  Une sélection de projets web et d’applications sur lesquels j’ai travaillé,
  allant de plateformes métiers à grande échelle à des produits plus ciblés.
  Chaque projet présente son contexte, les enjeux rencontrés et les solutions
  mises en œuvre.
</p>

<section class="projects-grid">
  {% for project in site.projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</section>
