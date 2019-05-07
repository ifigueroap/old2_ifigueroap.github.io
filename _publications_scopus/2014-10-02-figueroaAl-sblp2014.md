---
title: "Effect Capabilities for Haskell"
collection: publications_scopus
permalink: /publication/scopus/figueroaAl-sblp2014
year: 2014
date: 2014-10-02
venue: 'Brazilian Symposium on Programming Languages'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-319-11863-5_7'
author: Ismael Figueroa, Nicolas Tabareau, Éric Tanter
---

# Abstract

Computational effects complicate the tasks of reasoning about and maintaining software, due to the many kinds of interferences that can occur. While different proposals have been formulated to alleviate the fragility and burden of dealing with specific effects, such as state or exceptions, there is no prevalent robust mechanism that addresses the general interference issue. Building upon the idea of capability-based security, we propose effect capabilities as an effective and flexible manner to control monadic effects and their interferences. Capabilities can be selectively shared between modules to establish secure effect-centric coordination. We further refine capabilities with type-based permission lattices to allow fine-grained decomposition of authority. We provide an implementation of effect capabilities in Haskell, using type classes to establish a way to statically share capabilities between modules, as well as to check proper access permissions to effects at compile time. We exemplify how to tame effect interferences using effect capabilities, by treating state and exceptions.