---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<h2>Working Papers</h2>
{% for post in site.publications reversed %}
  {% if post.collection == 'workingpapers' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<h2>Publications</h2>
{% for post in site.publications reversed %}
  {% if post.collection == 'publications' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<h2>Selected Work in Progress</h2>
<p>Revealed Preferences and Social Interactions</p>
<p>Identification and Estimation of Nonlinear Peer Effects</p>
