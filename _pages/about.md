---
permalink: /
title: " "
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
{% include base_path %}
I am a Ph.D. candidate in the Department of Economics at the University of Cologne, Germany. I am affiliated with the [ECONtribute: Markets & Public Policy](https://econtribute.de/about-us-econtribute/) Cluster of Excellence.  I recently transferred from the University of Mannheim, where I started my PhD. I previously worked as a researcher at [ZEW](https://www.zew.de/en/) -- Leibniz Center for European Economic Research.


I will be on the 2024-25 Job Market.
<!--Before starting my PhD, I interned at the University of California
Santa Barbara as a research assistant with Pr. Youssef Benzarti, working on
taxation. I hold an MSc in Economics from ENSAE/Polytechnique specializing in Microeconomics
and Public Economics. -->

References available upon request.

## My research 
### Working papers
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} 


### Work in progress
{% for post in site.drafts reversed %}
  {% include archive-single.html %}
{% endfor %}





