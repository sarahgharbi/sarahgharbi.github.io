---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a second year PhD student in taxation at  the University of Mannheim (Germany) and work for ZEW -- Leibniz-Zentrum für Europäische Wirtschaftsforschung.
My supervisors are Pr. Sebastian Siegloch and Pr. Johannes Voget. 

Previously, I interned at the University of California
Santa Barbara as a research assistant with Pr. Youssef Benzarti, working on
taxation. I hold a MSc in Economics from ENS Paris-Saclay where I specialized in Microeconomics
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
