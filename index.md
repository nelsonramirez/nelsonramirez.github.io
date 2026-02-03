---
layout: plain
title: Welcome
headerTitle: Hi, I am Nelson
description: nothing
grouped: true
hide_description: true
hide_image: false
cover: false
---

# Hola!
### I’m Nelson Ramirez

I’m a frontend developer and data analyst living in France, and when I’m not coding, I’m making music.

I love combining **technology, design, and data** to create meaningful experiences — whether that’s through building web applications, performing music, or playing football. Life is all about exploring, learning, and connecting, and that’s the journey I try to live every day.

I grew up discovering the beauty of Classic and Venezuelan music, teaching myself the **venezuelan Cuatro** and guitar. Along the way, I also discovered programming at a young age, and that curiosity quickly turned into a lifelong passion.



## Professional Journey
I’ve had the chance to work with amazing teams and bring ideas to life — from startups to large organizations, always focusing on **clean interfaces, performance, and user-centered design**:

<div class="professional">
  <div class="experience-grid">

  <!-- Augment -->
  <div class="experience-card">
  <div class="left">
      <div class="card-logo">
        <img src="/assets/img/logos/augment.png" alt="Augment Logo">
      </div>
    </div>
    <div class="right">
      <h3>Augment SAS</h3>
      <p class="role">Senior Frontend Engineer</p>
      <p class="desc">Responsible for the frontend of the 3D visualization platform used by 800k+ users, including catalog and online 3D editor development.</p>
    </div>
  </div>

  <!-- ENGIE Developer -->
  <div class="experience-card">
    <div class="left">
      <div class="card-logo">
        <img src="/assets/img/logos/engie.png" alt="ENGIE Logo">
      </div>
    </div>
    <div class="right">
      <h3>ENGIE Entreprises et Collectivités</h3>
      <p class="role">Frontend Developer</p>
      <p class="desc">Developed the Bill-e web app, enabling consolidated views of clients’ consumption and billing data across multiple sites.</p>
    </div>
  </div>

  <!-- ENGIE Chatbot -->
  <div class="experience-card">
    <div class="left">
      <div class="card-logo">
        <img src="/assets/img/logos/engie.png" alt="ENGIE Logo">
      </div>
    </div>
    <div class="right">
      <h3>ENGIE Entreprises et Collectivités</h3>
      <p class="role">Chatbot Developer & Data Analyst</p>
      <p class="desc">Built and deployed a chatbot on Microsoft Azure, automating customer support cases and analyzing performance with Power BI.</p>
    </div>
  </div>

  <!-- Altran -->
  <div class="experience-card">
    <div class="left">
      <div class="card-logo">
        <img src="/assets/img/logos/altran.png" alt="Altran Logo">
      </div>
    </div>
    <div class="right">
      <h3>Altran</h3>
      <p class="role">Engineer Intern</p>
      <p class="desc">Developed a guidance system for autonomous vehicles, including UX/UI design, algorithms, and embedded applications.</p>
    </div>
  </div>

  <!-- International -->
  <div class="experience-card">
    <div class="left">
      <div class="card-logo">
        <img src="/assets/img/logos/international.png" alt="International Logo" >
      </div>
    </div>
    <div class="right">
      <h3>International</h3>
      <p class="role">Frontend Engineer</p>
      <p class="desc">I’ve also contributed to web applications for startups and larger organizations abroad, building interfaces and architectures while collaborating in multicultural, agile teams.</p>
    </div>
  </div>

  </div>
</div>


## Academic Journey
I enjoy learning continuously and staying curious. Here’s a peek at my studies:

<div class="academic">
  
  <div class="experience-grid">
  <!-- DataScientest -->
  <div class="experience-card">
    <div class="card-logo">
      <img src="/assets/img/logos/liora.png" alt="DataScientest Logo" class="experience-logo">
    </div>
    <h3>DataScientest & Ecole des Mines de Paris</h3>
    <p class="role">Data Analyst Certification</p>
  </div>

  <!-- Université Paris-Saclay -->
  <div class="experience-card">
    <div class="card-logo">
    <img src="/assets/img/logos/paris-saclay.png" alt="Université Paris-Saclay Logo"  class="experience-logo">
    </div>
    <h3>Université Paris-Saclay</h3>
    <p class="role">Master’s Degree in Embedded Systems and Information Processing</p>
  </div>

  <!-- Université Paris Nanterre -->
  <div class="experience-card">
    <div class="card-logo">
    <img src="/assets/img/logos/paris-nanterre.png" alt="Université Paris Nanterre Logo"  class="experience-logo">
    </div>
    <h3>Université Paris Nanterre</h3>
    <p class="role">Diplôme d’Université Arts, Lettres et Langues</p>
  </div>

  <!-- Universidad Nacional Experimental del Táchira -->
  <div class="experience-card">
    <div class="card-logo">
      <img src="/assets/img/logos/unet.png" alt="UNET Logo" class="experience-logo">
    </div>
    <h3>Universidad Nacional Experimental del Táchira</h3>
    <p class="role">Diplôme d’ingénieur, Computer Engineering</p>
  </div>

  </div>

</div>



<section class="projects-grid">
  {% for project in site.projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</section>