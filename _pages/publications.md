---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

Publications
======

* “Asymmetric Information and Review Systems: The Challenge of Digital Platforms”, 2018, Economic Analysis of the Digital Revolution edited by J.J. Ganuza and G. Llobet

Working Papers
=====

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
