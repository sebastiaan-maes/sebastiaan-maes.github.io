---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<h2>Working Papers</h2>
{% for post in site.workingpapers reversed %}
    {% include archive-single.html %}
{% endfor %}

<br>
<h2>Publications</h2>
{% for post in site.publications reversed %}
    {% include archive-single.html %}
{% endfor %}
