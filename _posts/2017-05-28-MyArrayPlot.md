---
layout: post
title: "conferences NKS2006 pjl-nks-2006-presentation functions MyArrayPlot.nb"
gif: assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_90.gif
date: 2017-05-28
---

# MyArrayPlot

6.0 for Mac OS X (March 1, 2006)

{2006, 5, 18, 12, 11, 51.376242}

![MyArrayPlot_5.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_5.gif)

PointToSquare[{i_,j_}]: given a point {i,j}, takes the point as the bottom left corner of a unit square, and returns the Line primitives that draw the square.

![MyArrayPlot_7.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_7.gif)

![MyArrayPlot_8.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_8.gif)

![MyArrayPlot_9.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_9.gif)

![MyArrayPlot_10.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_10.gif)

![MyArrayPlot_11.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_11.gif)

![MyArrayPlot_12.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_12.gif)

![MyArrayPlot_13.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_13.gif)

materials-01.nb

![MyArrayPlot_15.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_15.gif)

![MyArrayPlot_16.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_16.gif)

Inefficient: generates all pairings of points on the lattice and then culls them.

Indexing works in the wrong way as well:

![MyArrayPlot_19.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_19.gif)

ArrayPlot indexing is from top left.  Default for MyArrayPlot is bottom left.  Output ArrayPlot indexing using 

![MyArrayPlot_21.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_21.gif)

![MyArrayPlot_22.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_22.gif)

Clean up the mesh drawing

![MyArrayPlot_24.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_24.gif)

![MyArrayPlot_25.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_25.gif)

![MyArrayPlot_26.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_26.gif)

![MyArrayPlot_27.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_27.gif)

![MyArrayPlot_28.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_28.gif)

![MyArrayPlot_29.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_29.gif)

![MyArrayPlot_30.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_30.gif)

indexing from top left and bottom right is implemented

CellDirectives option is NOT implemented

LineDirective options with points outside the array generates an error and Null is returned

![MyArrayPlot_35.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_35.gif)

![MyArrayPlot_36.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_36.gif)

![MyArrayPlot_37.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_37.gif)

![MyArrayPlot_38.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_38.gif)

e.g.

Specifying the border of a single cell to be highlighted, using the LineDirectives option.

![MyArrayPlot_41.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_41.gif)

![MyArrayPlot_42.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_42.gif)

![MyArrayPlot_43.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_43.gif)

![MyArrayPlot_44.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_44.gif)

![MyArrayPlot_45.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_45.gif)

![MyArrayPlot_46.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_46.gif)

![MyArrayPlot_47.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_47.gif)

![MyArrayPlot_48.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_48.gif)

![MyArrayPlot_49.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_49.gif)

![MyArrayPlot_50.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_50.gif)

Without the mesh.

![MyArrayPlot_52.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_52.gif)

![MyArrayPlot_53.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_53.gif)

Points outside the array give an error.

![MyArrayPlot_55.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_55.gif)

Similar tests for a non-square array.

![MyArrayPlot_57.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_57.gif)

![MyArrayPlot_58.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_58.gif)

![MyArrayPlot_59.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_59.gif)

![MyArrayPlot_60.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_60.gif)

![MyArrayPlot_61.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_61.gif)

![MyArrayPlot_62.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_62.gif)

![MyArrayPlot_63.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_63.gif)

![MyArrayPlot_64.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_64.gif)

![MyArrayPlot_65.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_65.gif)

![MyArrayPlot_66.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_66.gif)

![MyArrayPlot_67.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_67.gif)

![MyArrayPlot_68.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_68.gif)

![MyArrayPlot_69.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_69.gif)

![MyArrayPlot_70.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_70.gif)

![MyArrayPlot_71.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_71.gif)

1.

LineDirectives only works with both a color and a thickess specified

e.g.

![MyArrayPlot_75.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_75.gif)

![MyArrayPlot_76.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_76.gif)

works when both a color and a thickness are specified

![MyArrayPlot_78.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_78.gif)

![MyArrayPlot_79.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_79.gif)

2.

LineDirectives are rendered after the mesh:

e.g.

want the whole square to be red, but instead only the border is:

![MyArrayPlot_84.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_84.gif)

![MyArrayPlot_85.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_85.gif)

![MyArrayPlot_86.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_86.gif)

![MyArrayPlot_87.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_87.gif)

![MyArrayPlot_88.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_88.gif)

![MyArrayPlot_89.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_89.gif)

![MyArrayPlot_90.gif](../../../assets/2017/05/28/MyArrayPlot-500px/MyArrayPlot_90.gif)

