---
title: "Taming Aspects with Monads and Membranes"
collection: publications_scopus
permalink: /publication/scopus/figueroaAl-foal2013
year: 2013
date: 2013-03-26
venue: 'International Workshop on Foundations of Aspect-Oriented Languages'
paperurl: 'https://dl.acm.org/citation.cfm?doid=2451598.2451600'
author: Ismael Figueroa, Nicolas Tabareau, Éric Tanter
---

# Abstract

When a software system is developed using several aspects, special care must be taken to ensure that the resulting behavior is correct. This is known as the aspect interference problem, and existing approaches essentially aim to detect whether a system exhibits problematic interferences of aspects. In this paper we describe how to control aspect interference by construction by relying on the type system. More precisely, we combine a monadic embedding of the pointcut/advice model in Haskell with the notion of membranes for aspect-oriented programming. Aspects must explicitly declare the side effectsa nd the context they can act upon. Allowed patterns of control flow interference are declared at the membrane level and statically enforced. Finally, computational interference between aspects is controlled by the membrane topology. To combine independent and reusable aspects and monadic components into a program specification we use monad views, a recent technique for conveniently handling the monadic stack.