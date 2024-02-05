---
layout: archive
title: "Skills"
permalink: /skills/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

*Laboratory*  
1. Lab skills
2. More lab skills

*Data analysis*  
1. Data  
2. Data  

*Field & Other skills*  
1. Field  

*Languages*  
1. English  
2. Russian  
3. Spanish  
