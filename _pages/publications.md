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
  - Staggered difference-in-differences design on 550K residential parcels to estimate the trade-off between lost tax capacity from easements and the market value spillovers from those nearby easements.
  - Draft (May 2025) — [PDF]({{ '/files/conservation-easement-externalities.pdf' | relative_url }})

- **Transportation Changes Land Use: How the St. Croix Bridge Shaped Accessibility, Housing Values, and Travel Behavior**
  - IV–difference-in-differences design to estimate the impact of the St. Croix Bridge opening on access and how that access capitalizes into higher land and improvement values.
  - Wrote with Eric Lind at the [Accessibility Observatory](https://www.cts.umn.edu/programs/ao) using in-house access data.
  - Presented at the Transportation Research Board Annual Meeting (2026) and the CTS Transportation Research Conference (2025).

- **Rent Control Capitalization into Land Values: Evidence from New Jersey's New Construction Exemption**
  - Triple-difference design on 2024 assessed values exploiting New Jersey's New Construction Exemption. The law change permitted newly built 4+ unit buildings to be excluded from the city's rent control ordinance.
  - I find a land value premium of approximately 4.7%, significant at all three legislative cutoffs (1987, 1992, 1997), with a positive but largely mechanical effect on building (improvement) values.
  - Draft (June 2026) — [PDF]({{ '/files/rent-control-capitalization.pdf' | relative_url }})

- **When Do Local Income Taxes Cause Residential Sorting? Evidence from Pennsylvania's Piecewise Earned Income Tax**
  - Continuous stacked difference-in-differences on LEHD/LODES worker flows (2002–2019) identifying a causal effect from Pennsylvania's piecewise local Earned Income Tax. 
  - Major contributions of the paper:
    - Municipal level income tax effects.
    - The binding decomposition that isolates rate changes that move a worker's tax bill above the worker tax.
  - I find residential sorting away from binding municipal increases.
  - Draft (May 2026) — [PDF]({{ '/files/local-income-tax-sorting.pdf' | relative_url }})

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
