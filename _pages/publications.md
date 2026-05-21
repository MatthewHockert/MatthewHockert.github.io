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

I am developing several research papers as part of my dissertation and related projects. These works span different stages of the research process — from data collection and model design to drafting and presentation.

### Dissertation Papers

- **Conservation and Externalities: The Effect of Conservation Easements on Neighboring Residential Parcels**
  - Staggered difference-in-differences on 550K residential parcels; estimates property tax and value spillovers from nearby easements.

- **Transportation Changes Land Use: How the St. Croix Bridge Shaped Accessibility, Housing Values, and Travel Behavior**
  - IV–difference-in-differences exploiting a bridge opening; decomposes accessibility capitalization into land vs. improvement values.
  - Developed with Eric Lind at the [Accessibility Observatory](https://www.cts.umn.edu/programs/ao) using in-house data. Presented at the Transportation Research Board Annual Meeting (2026) and the CTS Transportation Research Conference (2025).

- **Rent Control Capitalization into Land Values: Evidence from New Jersey's New Construction Exemption**
  - Triple-difference design on 2024 assessed values exploiting New Jersey's New Construction Exemption (a rent-control exemption for newly built 4+ unit buildings); finds a 54% land value premium, concentrated in land with no effect on structures.
  - Draft (April 2026) — [PDF]({{ '/files/rent-control-capitalization.pdf' | relative_url }}) · comments welcome.

### Additional Research

- **Restrictive Rules, Restrained Housing: Rent Control Policies and Their Local Impacts**
  - Developed an LLM-based algorithm to extract and classify rent control ordinances across 35 variables from municipal codes spanning 111 New Jersey jurisdictions.

As I begin the publishing and public sharing phase of my research, you'll be able to find the code for my projects on my [GitHub](https://github.com/MatthewHockert).

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
