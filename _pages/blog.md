---
layout: single
title: "Blog"
permalink: /blog/
author_profile: true
---
<h2>Personal Note</h2>
<em>
The views expressed here are my own and do not reflect the opinions or positions of my employer(s).
The ideas discussed in my writing explore hypothetical, data-driven scenarios and are subject to revision as new information becomes available.
</em>

<h2>Featured Publication</h2>
<p>
  <a href="https://www.cts.umn.edu/ao/accountabilitythroughaccessibility/executivesummary" target="_blank" rel="noopener">
    <strong>Accountability Through Accessibility – Executive Summary</strong>
  </a><br>
  <em>My paper "Transportation Changes Land Use: How the St. Croix Bridge Shaped Accessibility, Housing Values, and Travel Behavior" was summarized into a white paper which includes all work done by my coworkers at the at the
  <a href="https://www.cts.umn.edu/programs/ao" target="_blank" rel="noopener">Accessibility Observatory</a>.</em>
</p>
<hr>

<h2>My Writing</h2>
{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
    {% if post.summary %}
      <p>{{ post.summary }}</p>
    {% else %}
      <p>{{ post.excerpt }}</p>
    {% endif %}
  </article>
{% endfor %}