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

- **_PhD in Computer Science_**, University of Chile and École des Mines de Nantes, 2014
- _Bachelor in Computer Science_, University of Santiago, 2010

### Work experience

- **_Lead Software Engineer_** at [Spotmind](https://www.spotmind.cl)
- _External Professor_ at [Computer Science Department (DCC)](https://dcc.uchile.cl), University of Chile

### Previous experiences

- Nov/2020 through Nov/2022: **_Lead Software Engineer_** at [SP Digital](https://spdigital.cl)
- Aug/2019 through Sept/2020: **_Associate Professor_**, [Universidad de Valparaíso](http://www.uv.cl)
  - [Carrera de Ingeniería en Información y Control de Gestión](http://iicg.uv.cl)
  - Duties included: Research, Teaching, Student Reach, Website maintenance
- Apr/2019 through Jul/2019: **_Senior Researcher_** at [Inria Chile](http://www.inria.cl)
- Jan/2015 through Jan/2019: **_Associate Professor_**
  - [Escuela de Ingeniería Informática](http://www.inf.ucv.cl), [Pontificia Universidad Católica de Valparaíso](http://www.pucv.cl)
  - Duties included: Research, Teaching, Head of local IT department

### WoS Publications ({{site.publications_wos|size}})

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
