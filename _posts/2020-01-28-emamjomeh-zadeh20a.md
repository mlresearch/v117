---
title: Interactive Learning of a Dynamic Structure
abstract: 'We propose a general framework for interactively learning combinatorial
  structures, such as (binary or non-binary) classifiers, orderings/rankings of items,
  or clusterings, when the underlying structure changes over time. Inspired by Angluin’s
  equivalence query model, the algorithm proposes a structure in each round, and it
  either learns that its proposal is the true structure in this round, or it observes
  a specific mistake in the proposal. The feedback is correct only with probability
  $1 - p$, and adversarially incorrect with probability $p$. The algorithm’s goal
  is to minimize its number of mistakes over the course of $R$ rounds. Our general
  framework is based on a graph representation of the structures and feedback in a
  static environment, proposed by Emamjomeh-Zadeh and Kempe (2017). To be able to
  learn efficiently, it is sufficient that there be a graph $G$ whose nodes are the
  candidate structures and whose (weighted) edges capture the possible feedback, satisfying
  a certain natural shortest paths property. To model the evolution of the underlying
  structure, we consider two natural models, which we term the Shifting Target model
  and Drifting Target model. In the former, the true structure always belongs to a
  small pool of candidate structures. In the latter, the structure can change only
  by transitioning along the edges of a known evolution graph. In order to achieve
  non-trivial results, we bound the total number of times the underlying structure
  can change, denoted by $B$. We provide upper and lower bounds on the number of mistakes,
  which depend on the total number of changes $B$, the total number of structures
  $n$, and natural measures of complexity of the dynamic models: the size of the pool
  of candidate structures in the Shifting Target model, and the maximum degree of
  the evolution graph in the Drifting Target model.'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: emamjomeh-zadeh20a
month: 0
tex_title: Interactive Learning of a Dynamic Structure
firstpage: 277
lastpage: 296
page: 277-296
order: 277
cycles: false
bibtex_author: Emamjomeh-Zadeh, Ehsan and Kempe, David and Mahdian, Mohammad and Schapire,
  Robert E.
author:
- given: Ehsan
  family: Emamjomeh-Zadeh
- given: David
  family: Kempe
- given: Mohammad
  family: Mahdian
- given: Robert E.
  family: Schapire
date: 2020-01-28
address: 
publisher: PMLR
container-title: Proceedings of the 31st International Conference  on Algorithmic
  Learning Theory
volume: '117'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 1
  - 28
pdf: http://proceedings.mlr.press/v117/emamjomeh-zadeh20a/emamjomeh-zadeh20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
