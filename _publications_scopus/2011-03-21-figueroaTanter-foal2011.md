---
title: "A Semantics for Execution Levels with Exceptions"
collection: publications_scopus
permalink: /publication/scopus/figueroaTanter-foal2011
year: 2011
date: 2011-03-21
venue: 'International Workshop on Foundations of Aspect-Oriented Languages'
paperurl: 'https://dl.acm.org/citation.cfm?id=1960513'
author: Ismael Figueroa, Éric Tanter
---

{{ author }}

# Abstract

Aspect-oriented languages are usually formulated as an extension to existing languages, without paying any special attention to the underlying exception handling mechanisms. Consequently, aspect exceptions and handlers are no different than base exceptions and handlers. Conflation between aspect and base exceptions and handlers may inadvertently trigger execution of unintended handlers, changing the expected program behavior: aspect exceptions are accidentally caught by base handlers or vice-versa. Programmers cannot state the desired interaction between aspect and base exceptions and handlers. Specific instances of this issue have been identified by others researchers. We distill the essence of the problem and designate it as the exception conflation problem. Consequently, we propose a semantics for an aspect-oriented language with execution levels and an exception handling mechanism that solves the exception conflation problem. By default, the language ensures there is no interaction between base and aspect exceptions and handlers, and provides level-shifting operators to flexibly specify interaction between them when required. We illustrate the benefits of our proposal with a representative set of examples