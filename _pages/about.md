---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a PhD candidate in Public Economics at the University of Cologne (Germany). I recently transferred from University of Mannheim following my supervisor Pr. Sebastian Siegloch. I previously worked as a junior researcher at ZEW -- Leibniz-Zentrum für Europäische Wirtschaftsforschung.


Before starting my PhD, I interned at the University of California
Santa Barbara as a research assistant with Pr. Youssef Benzarti, working on
taxation. I hold a MSc in Economics from ENSAE/Polytechnique where I specialized in Microeconomics
and Public Economics. 


References available upon request.

# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
