---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I hold a MSc in Economics from ENS Cachan where I specialized in microeconomics
and public economics. Currently, I am interning at the University of California
Santa Barbara as a research assistant with Pr. Youssef Benzarti, working on
fiscal incidence.

I plan to start a PhD program in public finance in Fall 2019.

References available upon request.

# Publications

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
