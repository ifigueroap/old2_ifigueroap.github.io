---
title: "Towards Progressive Program Verification in Dafny"
collection: publications_scopus
permalink: /publication/scopus/figueroaAl-sblp2018
year: 2018
date: 2018-09-20
venue: 'Brazilian Symposium on Programming Languages'
paperurl: 'https://dl.acm.org/citation.cfm?id=3264649'
author: Ismael Figueroa, Bruno García, Paul Leger
---

# Abstract

Program verification is a tool for the development of software that is free from defects and satisfies its functional specification. It suffers from two issues that have already been addressed in the field of type systems. First, it has a rigid focus on full-program verification. Also, it provides weak support for "partial" verification, relying on unproven lemmas that may lead to unsound runtime behavior. These issues are also present in Dafny, a verification-first programming language with full support for expressive pre-conditions and post-conditions that must be verified statically. Inspired by recent research on the field of gradual program verification in the Coq proof assistant, in this paper we present a first proposal for progressive verification in Dafny by presenting a minimal proof-of-concept implementation. Progressive verification means that programmers can use a new keyword to specify post-conditions that are assumed to be true during verification, but that will be tested at runtime by automatically-generated checks. We argue that our approach is correct by construction, by relying on the architecture of Dafny itself, and we also discuss several issues regarding the threats to the proposed approach as well as perspectives for further development.