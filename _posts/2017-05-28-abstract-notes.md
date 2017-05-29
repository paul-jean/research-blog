---
layout: post
title: "conferences NKS2006 abstract-notes.nb"
date: 2017-05-28
---

In the usual setup, an ECA is strictly Markovian: the new value of a cell depends only on the values of the cells in it's neighborhood on the previous time step.  I will introduce a way of relaxing the Markovian constraint, by allowing the value of the centre neighborhood cell to be referenced from a number of time steps in the past - so-called ECA with Memory (ECAM).  

A simple modification of Elementary Cellular Automata (ECA) will be introduced, whereby the value of the centre cell in the 3-cell neighborhood is referenced from a number of time steps in the past.  The amount of "memory" in the centre cell then constitutes a parametrization of ECA, called ECA with Memory (ECAM).  Given an ECA rule number, one simply specifies in addition the memory for the centre cell.  In the case of zero memory, one recovers the ECA.

Mathematically, an ECAM is a non-Markovian generalization of an ECA.  

This talks aims to give a guided tour through the corner of the computational universe occupied by ECAM.  Several key questions will be addressed:

1. How does the class of rule x ECAM compare to that of rule x ECA?  (This question is equivalent to analyzing the limit as memory goes to zero).  For example, is the rule 30 ECAM also class 3?

2. Are there mean-field estimates available for 

Extensive work on the statistical mechanics of cellular automata has been done by Wolfram [1] and others (e.g. []).  This work aims to extend these analyses to include the statistical mechanics of ECAM.

How does the behavior 

A mean-field theory for the density in ECAM will be presented, along with a 

Elementary Cellular Automata with Memory

Oral presentation

Simple modification of an ECA: add memory to the centre cell

(non-Markovian parametrization)

Emulations:

- exact emulation using a range-1 CA with more colors

- emulation in terms of space-time blocks

Statistical mechanics:

- discrete dynamical maps in density and their mean-field approximations

- exact and mean-field approximations to correlations

- response to perturbations

Analytical:

- Diffusion constant

- Growth rates

A simple modification of an Elementary Cellular Automaton will be presented, in which the centre cell of the three-cell neighborhood is referenced from a number of time steps in the past.  Two different emulations in terms of range-1 CAs will be described.  Analytical results for the bounds on finite growth rates and diffusion constants will also be given.  Exact results and mean-field approximations will be presented for statistical mechanical behavior, in particular discrete dynamical density maps, correlation functions, the growth of perturbations, and phase transitions.

