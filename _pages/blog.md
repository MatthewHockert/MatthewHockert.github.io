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

<h2>My Writing</h2>
{% for post in site.posts %}
  {% unless post.hidden %}
  <article>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    {% if post.summary %}
      <p>{{ post.summary }}</p>
    {% else %}
      <p>{{ post.excerpt }}</p>
    {% endif %}
  <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
  </article>
  {% endunless %}
{% endfor %}