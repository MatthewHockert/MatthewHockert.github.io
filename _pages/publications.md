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
  - Examines the spillover effects of conservation easements on neighboring property values and municipal tax bases in Hennepin County, MN.  
  - First full draft completed; currently under revision.  

- **Rent Control and Housing Supply: Evidence from a Staggered Difference-in-Differences Approach**  
  - Investigates the impact of rent control adoption on permitting and housing supply across U.S. cities.  
  - Preliminary models completed; refining analysis and drafting.  

- **Measuring Rent Control Intensity with Natural Language Processing and Generative Models**  
  - Uses municipal codes and NLP/AI techniques to create new indices of rent control restrictiveness across U.S. cities.  
  - Data collection and measurement framework in progress.  

- **Transportation Changes Land Use: How the St. Croix Bridge Shaped Accessibility, Housing Values, and Travel Behavior**  
  - Explores how infrastructure expansion reshapes accessibility, land use, and housing markets.  
  - Developed with Eric Lind at the [Accessibility Observatory](https://www.cts.umn.edu/programs/ao) using in-house data. Submitted for presentation; preparing for public release.  

As I begin the publishing and public sharing phase of my research you'll be able to find the code to my projects on my [github](https://github.com/MatthewHockert). 

---


## Publications

{% for post in site.publications reversed %}
    {% include archive-single.html %}
{% endfor %}

## Featured Publication

<p>
  <a href="https://www.cts.umn.edu/ao/accountabilitythroughaccessibility/executivesummary" target="_blank" rel="noopener">
    <strong>Accountability Through Accessibility – Measuring What Matters for Departments of Transportation</strong>
  </a><br>
  <em>My paper "Transportation Changes Land Use: How the St. Croix Bridge Shaped Accessibility, Housing Values, and Travel Behavior" was summarized into a white paper which includes work done by my coworkers at the
  <a href="https://www.cts.umn.edu/programs/ao" target="_blank" rel="noopener">Accessibility Observatory</a>.</em>
</p>
<hr>


