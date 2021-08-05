---
title: "Which Monads Haskell developers use: An exploratory study"
collection: publications_wos
permalink: /publication/wos/figueroaAl-scp2021
year: 2021
date: 2021-01-01
venue: 'Science of Computer Programming'
author: 'Ismael Figueroa, Paul Leger, Hiroaki Fukuda'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0167642320301313'
doi: '10.1016/j.scico.2020.102523'
quartil: 3
---

# Abstract

Monads are a mechanism for embedding and reasoning about notions of computation
such as mutable state, I/O, exceptions, and many others. Even though monads are
technically language-agnostic, they are mostly associated with the Haskell
language. Indeed, one could argue that the use of monads is one of the defining
characteristic of the Haskell language. In practical terms, monadic programming
in Haskell relies on the standard mtl package library, which provides eight
core notions of computation: identity, error, list, state, reader, writer, RWS,
and continuations. Despite their widespread use, we are not aware of any
empirical investigations regarding which monads are the most used by
developers. In this paper we present an empirical study that covers a snapshot
of available packages in the Hackage repository—covering 85135 packages and
more than five million Haskell files. To the best of our knowledge this is the
first large-scale analysis of Hackage with regards to monads and their usage as
dependencies. Our results show that around 30.8% of the packages depend on the
mtl package, whereas only 1.2% depend on alternative, yet compatible
implementations. Nevertheless, usage patterns for each specific monad remain
similar both for mtl and alternatives. Finally, the state monad is by far the
most popular one, although all of them are used. We also report on the
distribution of packages that use mtl, regarding their category and stability
level.