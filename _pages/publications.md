---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

## Publications and working papers

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% include base_path %}

## Resting papers

These are old papers that were never published but have a few
citations out there.

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
