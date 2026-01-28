---
layout: plain
title: Home
headerTitle: Hi, I am Nelson
description: >
  This is the `list` layout for showing blog posts, which shows just the title and groups them by year of publication.
  Check out the `blog` layout for comparison.
grouped: true
hide_description: false
hide_image: false
cover: true
---

<h1>Hola! <br>je suis Nelson</h1>

<p>
  Ingénieur en informatique spécialisé dans le développement frontend et les
  applications web, je conçois des interfaces claires, performantes et
  maintenables, avec une attention particulière portée à l’expérience
  utilisateur et à la qualité du code.
</p>

<p>
  J’ai travaillé sur des projets variés, notamment des applications métiers à
  forte contrainte, en collaboration étroite avec les équipes produit, design
  et techniques.
</p>

<p>
  Vous pouvez découvrir ci-dessous une sélection de mes projets récents.
</p>

<section class="projects-grid">
  {% for project in site.projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</section>