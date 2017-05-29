---
layout: post
title: "blog posts 2012 04 22 question-rule146-particle-control.nb"
gif: assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_18.gif
date: 2017-05-29
---

Can the trajectory of a particle in rule 146 be controlled?

Simplest case: 1 particle in the system, try to make it stay at the same position for all time.

Is there an initial condition that would achieve that?  Perhaps a perfectly symmetric one?

In an evolution where the particle stays at one position for all time, does the particle size distribution change vs an evolution where the particle meanders?  i.e. the run lengths of even runs, does the distribution of even run lengths change?

Is there some trade-off between the size of fluctuations in particle size and the deviation from a random walk?  I mean, if you try to control the particle trajectory, does it require messing with the size of the particle much?  I\[CloseCurlyQuote]m thinking of a Heisenberg uncertainty kind of thing, where localizing the particle in space means the momentum becomes uncertain.  Not sure what the right analogy is between momentum and particle size ... or if there\[CloseCurlyQuote]s any anology there at all.  Maybe particle size is literally like the mass?

![question-rule146-particle-control_2.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_2.gif)

![question-rule146-particle-control_3.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_3.gif)

![question-rule146-particle-control_4.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_4.gif)

![question-rule146-particle-control_5.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_5.gif)

![question-rule146-particle-control_6.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_6.gif)

![question-rule146-particle-control_7.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_7.gif)

![question-rule146-particle-control_8.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_8.gif)

![question-rule146-particle-control_9.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_9.gif)

![question-rule146-particle-control_10.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_10.gif)

![question-rule146-particle-control_11.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_11.gif)

![question-rule146-particle-control_12.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_12.gif)

![question-rule146-particle-control_13.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_13.gif)

Hmmm, I thik it\[CloseCurlyQuote]s impossible to have a perfectly symmetric initial condition that has an odd run on the boundary, such that no particle appears there.

![question-rule146-particle-control_15.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_15.gif)

![question-rule146-particle-control_16.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_16.gif)

![question-rule146-particle-control_17.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_17.gif)

![question-rule146-particle-control_18.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_18.gif)

So I have to put the single particle on the boundary intentionally, and then RotateRight ...

![question-rule146-particle-control_20.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_20.gif)

![question-rule146-particle-control_21.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_21.gif)

![question-rule146-particle-control_22.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_22.gif)

![question-rule146-particle-control_23.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_23.gif)

![question-rule146-particle-control_24.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_24.gif)

![question-rule146-particle-control_25.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_25.gif)

Right that works, but I happened to choose a width close to 2^n so there was a big annihilation:

![question-rule146-particle-control_27.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_27.gif)

![question-rule146-particle-control_28.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_28.gif)

Choose a different width:

![question-rule146-particle-control_30.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_30.gif)

![question-rule146-particle-control_31.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_31.gif)

![question-rule146-particle-control_32.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_32.gif)

![question-rule146-particle-control_33.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_33.gif)

![question-rule146-particle-control_34.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_34.gif)

![question-rule146-particle-control_35.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_35.gif)

![question-rule146-particle-control_37.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_37.gif)

![question-rule146-particle-control_38.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_38.gif)

![question-rule146-particle-control_39.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_39.gif)

![question-rule146-particle-control_40.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_40.gif)

![question-rule146-particle-control_41.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_41.gif)

![question-rule146-particle-control_42.gif](../../../assets/2017/05/29/question-rule146-particle-control-500px/question-rule146-particle-control_42.gif)

