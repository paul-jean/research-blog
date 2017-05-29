---
layout: post
title: "conferences NKSMidwest2008 talk NKS-Midwest-Letourneau-presentation.nb"
gif: assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_66.gif
date: 2017-05-29
---

# Monoliths in ECA Rule 146: New Insights

### Paul-Jean Letourneau, Wolfram Research

### NKS Midwest Conference, Oct 31, 2008

# Elementary Cellular Automata

### Elementary Cellular Automata (ECA) consist of a line of cells, updated according to a simple rule

### The rule specifies what the new color of a site should be based on its present color the color of its neighbors (the "neighborhood")

![NKS-Midwest-Letourneau-presentation_7.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_7.gif)

### Displaying each successive step down the page gives a history of the evolution

### Even from very simple initial conditions, ECA can do very complex things, as rule 30 does here

![NKS-Midwest-Letourneau-presentation_10.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_10.gif)

# Class 3 ECA Rules

### Rule 30 is an example of a so-called "class 3" ECA rule, meaning it is "complex"

### Class 3 rules show largely random behavior

### The plot below shows how several class 3 rules behave from a random initial condition

### The Principle of Computational Equivalence (PCE) claims that class 3 rules are universal

### Therefore, studying class 3 rules is a big focus in NKS

### This talk focusses on ECA rule 146,  in the bottom right-hand corner

![NKS-Midwest-Letourneau-presentation_18.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_18.gif)

# Monoliths in Rule 146

### I first saw this surprising behavior in ECA rule 146 in 2004

### Note the unusually large triangles coming out in a regular array, decreasing in size with time

![NKS-Midwest-Letourneau-presentation_22.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_22.gif)

# Why Are Monoliths Interesting?

### Fluctuations: Monoliths represent large fluctuations in a system apparently at equilibrium

### Nonequilibrium physics and phase transitions: Are there similar effects in real physical systems?

### Rare effect: Annihilations of this form seem to be rare amongst class 3 rules

### The PCE connection: Understanding them may help to understand how to use rule 146 (and possibly other related class 3 rules) to do computations

![NKS-Midwest-Letourneau-presentation_28.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_28.gif)

# Approach to Understanding Rule 146

### Solve a simpler problem

### Notice that the rule tables for rule 146 and rule 90 differ in only 3 spots

### The rules give different outputs when when there are adjacent black cells in the input

![NKS-Midwest-Letourneau-presentation_33.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_33.gif)

### The output from a single black cell is identical because 90 doesn't generate adjacent blacks in this case

![NKS-Midwest-Letourneau-presentation_35.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_35.gif)

# The Difference Between 90 and 146

### Under what conditions to adjacent blacks appear in rule 90?

### The Manipulate shows that blacks separated by even runs of whites evolve to give adjacent blacks

### Once the adjacent blacks appear, as we saw must be the case from the rule tables, the rules evolve differently

![NKS-Midwest-Letourneau-presentation_41.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_41.gif)

# Highlight the Differences

### If we highlight the even runs, we'll see how 146 differs from 90

### Highlight even runs of whites in red, adjacent blacks in blue

### Interesting!  We see a series of even-run triangles (red), connected by pairs of 1's (blue)

![NKS-Midwest-Letourneau-presentation_46.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_46.gif)

# Persistent Structures

### With a larger evolution, it's clear that even runs form a persistent structure!

![NKS-Midwest-Letourneau-presentation_49.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_49.gif)

# Persistent Structures

### From random initial conditions, 146 forms a number of these structures after an initial transient

### Between the structures, there are only odd runs of whites and no adjacent blacks, so the evolution is rule 90

### So 146 evolves as rule 90 with interruptions, or perturbations, in the form of these localized structures

![NKS-Midwest-Letourneau-presentation_54.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_54.gif)

# Persistent Structures and Monoliths

### Here is what the monoliths look like with the even runs highlighted

### There are a lot of things going on here

### Clearly the structures can annihilate if they collide

### The structures also look like they feed into the monoliths

![NKS-Midwest-Letourneau-presentation_60.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_60.gif)

# Properties of Peristent Structures

### What are the properties of the structures?

### How long do they persist for?

### If there is only one of them, it seems to go forever (as long as there isn't a total annihilation)

### This plot shows a continuous run with a single structure

![NKS-Midwest-Letourneau-presentation_66.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_66.gif)

# Persistent Structure Triangle Size Distribution

### How large are the triangles in the structure?

### This plot shows the distribution of widths of even runs on a single structure

### The blue line is an exponential fit to the distribution

![NKS-Midwest-Letourneau-presentation_71.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_71.gif)

# Persistent Structure Movement

### This plot shows the movement of the persistent structure over time

### It would be interesting to study the difference of this movement from a random walk

![NKS-Midwest-Letourneau-presentation_75.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_75.gif)

# Information Transmission Through Structures

### How do the structures effect the flow of information in the system?

### (A) start with two structures

(B) perturb a site between boundaries

(C) difference pattern is nearly additive (compare G for rule 90)

(D) overlayed difference pattern shows non-additive differences follow phase boundaries

### (E through H) the same for 90

### This gives us a sense for how information from one site is transmitted to another in rule 146

### It looks like there are two modes of information: the linear part and the nonlinear part

### The linear part is what you get from an additive system (rule 90); it gets transmitted through the boundary

### The nonlinear part is reflected off the boundary

![NKS-Midwest-Letourneau-presentation_84.gif](../../../assets/2017/05/29/NKS-Midwest-Letourneau-presentation-500px/NKS-Midwest-Letourneau-presentation_84.gif)

# Conclusions

### Rule 146 is a class 3 rule that generates unusually large triangles ("monoliths")

### Highlighting even runs reveals localized structures

### The structures seem to do random walks, and only annihilate when they interact

### Information is transmitted in an interesting way through the structures

