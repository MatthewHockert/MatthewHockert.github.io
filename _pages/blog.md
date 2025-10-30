---
layout: single
title: "Blog"
permalink: /blog/
author_profile: true
---

<h2>Featured Publication</h2>
<p>
  <a href="https://www.cts.umn.edu/ao/accountabilitythroughaccessibility/executivesummary" target="_blank" rel="noopener">
    Accountability Through Accessibility – Executive Summary
  </a>
</p>
<hr>

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
    <p>{{ post.excerpt }}</p>
  </article>
{% endfor %}