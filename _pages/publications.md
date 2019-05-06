---
layout: archive
title: "Full List of Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

# Web of Science

{% for post in site.publications_wos reversed %}
  {% include archive-single.html %}
{% endfor %}

# Scopus

{% for post in site.publications_scopus reversed %}
  {% include archive-single.html %}
{% endfor %}

# Others

{% for post in site.publications_others reversed %}
  {% include archive-single.html %}
{% endfor %}
