---
section: theory
title: Bayesian Algorithms for Causal Data Mining
abstract: We present two Bayesian algorithms CD-B and CD-H for discovering unconfounded
  cause and effect relationships from observational data without assuming causal sufficiency
  which precludes hidden common causes for the observed variables. The CD-B algorithm
  first estimates the Markov blanket of a node \emph{X} using a Bayesian greedy search
  method and then applies Bayesian scoring methods to discriminate the parents and
  children of \emph{X}. Using the set of parents and set of children CD-B constructs
  a global Bayesian network and outputs the causal effects of a node \emph{X} based
  on the identification of Y arcs. Recall that if a node \emph{X} has two parent nodes
  \emph{A, B} and a child node \emph{C} such that there is no arc between \emph{A,
  B} and \emph{A, B} are not parents of \emph{C}, then the arc from \emph{X} to \emph{C}
  is called a Y arc. The CD-H algorithm uses the MMPC algorithm to estimate the union
  of parents and children of a target node \emph{X}. The subsequent steps are similar
  to those of CD-B. We evaluated the CD-B and CD-H algorithms empirically based on
  simulated data from four different Bayesian networks. We also present comparative
  results based on the identification of Y structures and Y arcs from the output of
  the PC, MMHC and FCI algorithms. The results appear promising for mining causal
  relationships that are unconfounded by hidden variables from observational data.
pdf: "./mani10a/mani10a.pdf"
layout: inproceedings
key: mani10a
month: 0
firstpage: 121
lastpage: 136
origpdf: http://jmlr.org/proceedings/papers/v6/mani10a/mani10a.pdf
sections: 
authors:
- given: Subramani
  family: Mani
- given: Constantin F.
  family: Aliferis
- given: Alexander
  family: Statnikov
---
