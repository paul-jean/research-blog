---
layout: post
title: "blog posts 2010 10 30 rule-18-random-walk.nb"
gif: assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_37.gif
date: 2017-05-29
---

# part 1

In [Eloranta1992], Eloranta proves that a single 'kink' (a persistent structure formed from even runs of white cells) in rule 18 performs a random walk.  Rule 18 is a close relative of rule 146.  In fact, they behave identically as long as there are no runs of black cells more than 2 cells wide, and those only ever occur in the initial transient of either rule.  So it's pretty clear that Eloranta's result applies to rule 146 just as well.

I've been reading through the proof.  I don't really understand it (because I suck at reading proofs).  But it occured to me that if rule 18 is run with a random initial condition of finite width, say 100 cells wide, then the output could only really be psuedorandom, since a finite random input is only psuedorandom.

But that got me thinking ...  is it possible that rule 18 could be adding additional randomness to the movement of the structure?  Rule 18 can do some complicated stuff, even from very small initial conditions, and it seems likely that it generates randomness on its own.  In the NKS book, Stephen Wolfram calls this Intrinsic Randomness Generation (IRG).

So could rule 18 be somehow adding to the randomness of the  movement of its persistent structures through IRG?

Here's what a single one of these structures looks like, evolving from a random (*ahem*, psuedorandom) initial condition of width 200 cells (and note the trick for creating an initial condition with only one even run of white cells in the center, which I think I got from Todd Rowland):

![rule-18-random-walk_4.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_4.gif)

![rule-18-random-walk_5.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_5.gif)

![rule-18-random-walk_6.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_6.gif)

![rule-18-random-walk_7.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_7.gif)

![rule-18-random-walk_8.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_8.gif)

![rule-18-random-walk_9.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_9.gif)

![rule-18-random-walk_10.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_10.gif)

I need a way of tracking the position of the structure, so I can test how random its movement is:

![rule-18-random-walk_12.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_12.gif)

![rule-18-random-walk_13.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_13.gif)

![rule-18-random-walk_15.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_15.gif)

![rule-18-random-walk_16.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_16.gif)

![rule-18-random-walk_17.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_17.gif)

![rule-18-random-walk_19.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_19.gif)

![rule-18-random-walk_20.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_20.gif)

![rule-18-random-walk_21.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_21.gif)

![rule-18-random-walk_22.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_22.gif)

![rule-18-random-walk_23.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_23.gif)

![rule-18-random-walk_24.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_24.gif)

![rule-18-random-walk_26.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_26.gif)

![rule-18-random-walk_27.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_27.gif)

![rule-18-random-walk_29.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_29.gif)

![rule-18-random-walk_31.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_31.gif)

![rule-18-random-walk_32.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_32.gif)

![rule-18-random-walk_34.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_34.gif)

![rule-18-random-walk_35.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_35.gif)

![rule-18-random-walk_36.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_36.gif)

![rule-18-random-walk_37.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_37.gif)

![rule-18-random-walk_39.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_39.gif)

![rule-18-random-walk_40.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_40.gif)

![rule-18-random-walk_41.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_41.gif)

![rule-18-random-walk_42.gif](../../../assets/2017/05/29/rule-18-random-walk-500px/rule-18-random-walk_42.gif)

