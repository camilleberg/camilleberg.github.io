---
title: About
layout: page
---

<!-- ============================================================
     about.md
     The profile image src is resolved by Liquid:
       - external-image: false → prepends site.url + /
       - external-image: true  → uses the URL as-is
     ============================================================ -->
![Profile Image]({% if site.external-image %}{{ site.picture }}{% else %}{{ site.url }}/{{ site.picture }}{% endif %})

<!-- The <p> below is plain HTML inside Markdown — both work fine
     in Jekyll. We use HTML so we can add class attributes that
     custom.css can target without touching the theme's Sass. -->

<p>
  Hi! My name is Camille. I am a Ph.D student in Economics at the
  University of Washington. My research interests sit at the
  intersection of applied econometrics and labour economics — I
  spend most of my time thinking about causal identification and
  what we can actually learn from observational data.
</p>

<p>
  Outside of research I enjoy building small web tools, writing
  about things I'm learning, and exploring the Pacific Northwest.
</p>

<!-- ============================================================
     SKILLS
     The class "skill-list" is targeted by custom.css rule #11.
     Each <li> is turned into an inline chip with a wisteria
     background wash, so the default bullet is also hidden there.
     ============================================================ -->
<h2>Skills</h2>

<ul class="skill-list">
  <li>Python</li>
  <li>R</li>
  <li>Stata</li>
  <li>SQL · MySQL · MongoDB</li>
  <li>Git</li>
  <li>HTML · CSS · Sass</li>
  <li>JavaScript · ReactJS</li>
  <li>Bootstrap · Foundation</li>
  <li>Jekyll</li>
  <li>Docker</li>
  <li>Scrum · Kanban</li>
  <li>TDD · Continuous Integration</li>
</ul>

<!-- ============================================================
     PROJECTS
     These are placeholder links — replace the href values with
     real GitHub repo URLs when your projects are ready.
     The <a> tags will be styled by custom.css rule #4 (link color
     → --wisteria-blue).
     ============================================================ -->
<h2>Projects</h2>

<ul>
  <li><a href="https://github.com/camilleberg">Labour market automation study</a></li>
  <li><a href="https://github.com/camilleberg">Minimum wage replication</a></li>
  <li><a href="https://github.com/camilleberg">Housing price data pipeline</a></li>
</ul>
