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

# Web of Science ({{site.publications_wos | size}})
<ul>{% for post in site.publications_wos reversed %}
  <li>
    <a href="{{ base_path }}{{ post.url }}" rel="permalink"><b>{{ post.title }}</b></a>
    {% if post.author %}
      <br/>{{ post.author }}
    {% endif %}
    {% if post.venue %}
      <br/><i>{{ post.venue }}</i>.
    {% endif %}  
    {% if post.year %}<i>{{ post.year }}</i>.{% endif %}
    {% if post.quartil %} WoS Quartile {{ post.quartil }}.{% endif %}
  </li>  
{% endfor %}</ul>

# Scopus ({{site.publications_scopus | size}})
<ul>{% for post in site.publications_scopus reversed %}
  <li>
    <a href="{{ base_path }}{{ post.url }}" rel="permalink"><b>{{ post.title }}</b></a>
    {% if post.author %}
      <br/>{{ post.author }}
    {% endif %}
    {% if post.venue %}
      <br/><i>{{ post.venue }}</i>.
    {% endif %}  
    {% if post.year %}<i>{{ post.year }}</i>.{% endif %}
    {% if post.quartil %}WoS Quartile {{ post.quartil }}.{% endif %}
  </li>

{% endfor %}</ul>

<!-- # Others
{% for post in site.publications_others reversed %}
  {% include archive-single.html %}
{% endfor %} -->
