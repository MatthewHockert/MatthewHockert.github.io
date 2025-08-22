---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Works in Progress

I am currently developing several research papers as part of my dissertation and related projects. These works are ongoing and represent different stages of the research process — from data collection and model design to drafting and presentation.  

- **Conservation and Externalities: The Effect of Conservation Easements on Neighboring Residential Parcels**  
  Examines the spillover effects of conservation easements on neighboring property values and municipal tax bases.  

- **Rent Control and Housing Supply: Evidence from a Staggered Difference-in-Differences Approach**  
  Investigates the impact of rent control adoption on permitting and housing supply dynamics.  

- **Measuring Rent Control Intensity with Natural Language Processing and Generative Models**  
  Uses municipal codes and NLP/AI techniques to create new indices of rent control restrictiveness across U.S. cities.  

- **Transportation Changes Land Use: How the St. Croix Bridge Shaped Accessibility, Housing Values, and Travel Behavior**  
  A separate research project exploring the interaction between infrastructure expansion, accessibility, and land use change.  

---

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

