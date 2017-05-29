---
layout: post
title: "conferences NKS2006 talk nks2006-letourneau.nb"
date: 2017-05-29
---

# Elementary Cellular Automata (ECA)

In order to explain how an Elementary Cellular Automaton with Memory works, let me put it in the context of an ECA.

In an ECA, one has a row of cells, each either black or white.  Each cell is updated in parallel according to a simple rule that states what the new color of the cell should be, depending on its current color and that of its left and right neighbors.

![nks2006-letourneau_4.gif](../../../assets/2017/05/29/nks2006-letourneau-500px/nks2006-letourneau_4.gif)

There are 256 such rules, but only 88 remain after removing cases that are equivalent with respect to left-right reflection and black-white inversion.

# Elementary Cellular Automata cont'd

Although all the cells in a row are updated in parallel in a CA, this animation shows each cell being updated one at a time.

The red border shows the cell being updated, along with its neighborhood above it.  In the rule table at the bottom, the rule case that's being used for that particular cell is also highlighted in red.

