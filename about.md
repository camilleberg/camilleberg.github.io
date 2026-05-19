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
