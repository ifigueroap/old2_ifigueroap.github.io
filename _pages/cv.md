---
layout: archive
title: "Simple CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

### Education
* ***PhD in Computer Science***, University of Chile and École des Mines de Nantes, 2014
* Bachelor in Computer Science, University of Santiago, 2010

### Work experience
* Currently: ***Senior Researcher*** at [Inria Chile](http://www.inria.cl)
* Jan/2015 through Jan/2019: ***Associate Professor***
  * [Escuela de Ingeniería Informática](http://www.inf.ucv.cl), [Pontificia Universidad Católica de Valparaíso](http://www.pucv.cl)
  * Duties included: Research, Teaching, Head of local IT department

### WoS Publications ({{ site.publications_wos | size }})
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
    <!-- {% include archive-single-cv.html %} -->
  {% endfor %}</ul>

### Scopus Publications ({{ site.publications_scopus | size }})
See the full list [here](/publications)!
  
<!-- ### Talks
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
### Teaching
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
### Service and leadership
* Currently signed in to 43 different slack teams -->
