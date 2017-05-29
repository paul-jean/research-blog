---
layout: post
title: "blog UserInterfaceProgramming.nb"
gif: assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_24.gif
date: 2017-05-29
---

# Principles of Symbolic Interfaces

# The Principle of Programmatic Generation

# The Principle of Programmatic Generation

## Generating interfaces with programs is easy

![UserInterfaceProgramming_5.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_5.gif)

# The Principle of Programmatic Generation

## Programs can easily create palettes

# The Principle of Programmatic Generation

## Programs can easily create palettes

# The Principle of Programmatic Generation

## Programs can easily create toolbars

![UserInterfaceProgramming_12.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_12.gif)

# The Principle of Programmatic Generation

## Tweaking the program which generates an interface is easier than tweaking the interface

![UserInterfaceProgramming_15.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_15.gif)

### Copied interface code

![UserInterfaceProgramming_17.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_17.gif)

# The Principle of Programmatic Generation

## We use generators for nearly all of our user interfaces, including...

### The help viewer toolbar

### The package editor toolbar

### The preferences dialog

### The history dialog

![UserInterfaceProgramming_24.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_24.gif)

![UserInterfaceProgramming_25.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_25.gif)

# The Principle of Minimal Dynamics

# The Principle of Minimal Dynamics

## A refresher on how Dynamics work

When a Dynamic is evaluated for display, a full dependency graph is computed in the kernel, and any subsequent change to any variable in that dependency graph triggers another update.

# The Principle of Minimal Dynamics

![UserInterfaceProgramming_31.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_31.gif)

![UserInterfaceProgramming_32.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_32.gif)

# The Principle of Minimal Dynamics

## Manipulate wraps Dynamic around its first argument, so these tricks apply equally well to Manipulate

# The Principle of Minimal Dynamics -- Applications

# The Principle of Minimal Dynamics -- Applications

Here, the Dynamic is moved inside the expression as far as we can move it, which is the Plot command.  The LocatorPane is no longer suicidal, and well into a recovery program.

# The Principle of Minimal Dynamics

## Dynamic graphical elements can be mixed in with a list of static graphical elements to minimize computation

## Dynamics in primitive coordinates can minimize computation

The version below uses Deploy to avoid unwanted modification of static elements, reduces the number of Dynamic elements.

![UserInterfaceProgramming_42.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_42.gif)

# The Principle of Minimal Dynamics

## Dynamics in option values can minimize computation

Any front end option can have a Dynamic right-hand side.  Here are some very useful ones.

![UserInterfaceProgramming_46.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_46.gif)

# The Principle of Minimal Dynamics

## Dynamics don't belong in every option value, however

![UserInterfaceProgramming_49.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_49.gif)

# The Principle of Minimal Dynamics

## How Nested Dynamics work

When nested, an inner Dynamic can update independently of whether outer Dynamics have been triggered.  However, an outer Dynamic always force inner Dynamics to re-evaluate.

![UserInterfaceProgramming_53.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_53.gif)

![UserInterfaceProgramming_54.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_54.gif)

# The Principle of Minimal Dynamics

## Nested Dynamics can save effort by reducing the impact of a dependency change

If, in an example like the following, you expect b to change often when a does not, wrapping Dynamic around b will definitely bring a performance benefit.

![UserInterfaceProgramming_58.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_58.gif)

![UserInterfaceProgramming_59.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_59.gif)

![UserInterfaceProgramming_60.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_60.gif)

![UserInterfaceProgramming_61.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_61.gif)

# The Principle of Minimal Dynamics

## Minimizing Dynamic computation using With

Dynamic holds its first argument.  As with any function which holds its argument, the way to insert a precomputed value is using With.  In this example, arguments computed every time the Checkbox is toggled can be moved outside the scope of Dynamic using With.

![UserInterfaceProgramming_65.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_65.gif)

# The Principle of Minimal Dynamics

Using With speeds things up significantly, although it's still slightly slow because of the dense resulting Graphics3D image and the time it takes to render. Rasterize takes care of that problem.  Note that everything has now been precomputed and slipped straight into the Dynamic now.

![UserInterfaceProgramming_68.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_68.gif)

# The Principle of Maximum Encapsulation

# The Principle of Maximum Encapsulation

## Global variables are promiscuous

![UserInterfaceProgramming_72.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_72.gif)

# The Principle of Maximum Encapsulation

![UserInterfaceProgramming_74.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_74.gif)

But back to the original point, none of this would have been an issue if you used DynamicModule.

# The Principle of Maximum Encapsulation

## Initialization code should not require Shift+Enter to set up

![UserInterfaceProgramming_78.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_78.gif)

![UserInterfaceProgramming_79.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_79.gif)

![UserInterfaceProgramming_80.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_80.gif)

# The Principle of Maximum Encapsulation

## The Initialization option of DynamicModule is guaranteed to evaluate before its contents

But we run into a bit of a pickle here...the first evaluation produces a bad result because Needs["Splines`"] must evaluate in a separate evaluation before parsing the body of the expression.  DynamicModule will take care of this for us, but Shift+Enter does not!

![UserInterfaceProgramming_84.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_84.gif)

![UserInterfaceProgramming_85.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_85.gif)

# The Principle of Maximum Encapsulation

## Can be solved by two Needs[] statements...one to fulfill Shift+Enter evaluation and one to fulfill Dynamic evaluation

Note that this is only an issue because of $ContextPath.  Any other initialization code could have safely appeared one time inside of Initialization.

![UserInterfaceProgramming_89.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_89.gif)

![UserInterfaceProgramming_90.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_90.gif)

# The Principle of Maximum Encapsulation

## Encapsulation in Manipulate

The same Initialization principle holds for Manipulate as for DynamicModule.  Here is basically the same example using Manipulate.

![UserInterfaceProgramming_94.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_94.gif)

![UserInterfaceProgramming_95.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_95.gif)

![UserInterfaceProgramming_96.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_96.gif)

# The Principle of Maximum Encapsulation

## Encapsulation in Manipulate

SaveDefinitions can also be used for function definitions, although it doesn't always reach into packages correctly.  Nonetheless, it often works well, and is used in Demonstrations by default.

![UserInterfaceProgramming_100.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_100.gif)

![UserInterfaceProgramming_101.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_101.gif)

![UserInterfaceProgramming_102.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_102.gif)

# The Principle of Maximum Encapsulation

Use NotebookDirectory to track the notebook's location, and bundle your other files in the same directory.

![UserInterfaceProgramming_106.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_106.gif)

![UserInterfaceProgramming_107.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_107.gif)

# The Principle of Evaluation Blocking

# The Principle of Evaluation Blocking -- Defining Terms

## Preemptive evaluations

Preemptive evaluations demand that the kernel stop whatever it's doing and immediately respond.

### Dynamics

### Buttons with default options

### Event handlers

## Queued evaluations

Queued evaluations sit in a queue in the front end and are served to the kernel in a first-in-first-out manner

### Shift+Enter calculations

# The Principle of Evaluation Blocking

## Blocked evaluations

Any evaluation which must pause while getting input from the user is a blocking evaluation. Evaluations might also be considered to block if they simply take a very long time.

![UserInterfaceProgramming_123.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_123.gif)

![UserInterfaceProgramming_124.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_124.gif)

Since preemptive calculations have a timeout, it's a bad idea to block a preemptive evaluation.  The following type of bug can be a difficult one to find:

![UserInterfaceProgramming_126.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_126.gif)

# The Principle of Evaluation Blocking

## Buttons with Method->"Queued"

Buttons can use queued evaluation if they're expected to block.  However, quite significantly, that means the operation of a button may be delayed.

![UserInterfaceProgramming_130.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_130.gif)

![UserInterfaceProgramming_131.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_131.gif)

# The Principles of Symbolic Interfaces Summarized

![UserInterfaceProgramming_133.gif](../../../assets/2017/05/29/UserInterfaceProgramming-500px/UserInterfaceProgramming_133.gif)

# Styles for SlideShow

