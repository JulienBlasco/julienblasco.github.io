---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

## Work in progress

{% for post in site.inprogress reversed %}
  {% include archive-single-inprogress.html %}
{% endfor %}

## Peer-reviewed

{% for post in site.publications reversed %}
  {% include archive-single-research.html %}
{% endfor %}

## Other published work
