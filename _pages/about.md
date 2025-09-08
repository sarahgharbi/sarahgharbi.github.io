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


I am a postdoctoral researcher the [Rockwool Foundation Berlin](https://www.rfberlin.com) (RFBerlin).

I obtained a PhD degree in Economics from the University of Cologne in 2025. Prior to joining the University of Cologne in 2022, I was a PhD student at the University of Mannheim and worked as a researcher in the group "Inequality and Public Policy" at the [ZEW](https://www.zew.de/en/) -- Leibniz Center for European Economic Research.


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





