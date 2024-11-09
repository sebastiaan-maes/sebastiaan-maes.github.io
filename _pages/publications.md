---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<h2>Working papers</h2>
{% for post in site.workingpapers reversed %}
    {% include archive-single.html %}
{% endfor %}

<br>
<h2>Publications</h2>
{% for post in site.publications reversed %}
    {% include archive-single.html %}
{% endfor %}

<br>
<h2>Selected work in progress</h2>
<h3 class="archive__item-title" itemprop="headline">Disentangling Peer Effects</h3>
<p>Joint with Raghav Malhotra <br> </p>
