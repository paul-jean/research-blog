---
layout: post
title: "conferences NKS2006 pjl-nks-2006-presentation functions ArrayPlotWithLegend.nb"
gif: assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_10.gif
date: 2017-05-28
---

meeting-peter-032406-03.nb

![ArrayPlotWithLegend_2.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_2.gif)

ArrayPlotWithLegend[m_,opts___] displays an ArrayPlot with a color bar on the right-hand side.

![ArrayPlotWithLegend_4.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_4.gif)

![ArrayPlotWithLegend_5.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_5.gif)

![ArrayPlotWithLegend_6.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_6.gif)

LegendBar[m_,opts___] creates the color bar for ArrayPlotWithLegend

![ArrayPlotWithLegend_8.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_8.gif)

![ArrayPlotWithLegend_9.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_9.gif)

![ArrayPlotWithLegend_10.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_10.gif)

ColorFunction and ColorFunctionScaling for the ArrayPlot is not reflected in the legend:

From ECAM-densities-14

![ArrayPlotWithLegend_13.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_13.gif)

![ArrayPlotWithLegend_14.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_14.gif)

Here there is no change to the default ColorFunction of GrayLevel, so the plot colors are reflected accurately in the legend.

![ArrayPlotWithLegend_16.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_16.gif)

Using Hue as the ColorFunction, which requires scaling, is not reflected in the colors of the legend.

![ArrayPlotWithLegend_18.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_18.gif)

![ArrayPlotWithLegend_19.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_19.gif)

![ArrayPlotWithLegend_20.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_20.gif)

Absolute grey levels (no scaling):

![ArrayPlotWithLegend_22.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_22.gif)

With Scaling

![ArrayPlotWithLegend_24.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_24.gif)

![ArrayPlotWithLegend_25.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_25.gif)

![ArrayPlotWithLegend_26.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_26.gif)

![ArrayPlotWithLegend_27.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_27.gif)

![ArrayPlotWithLegend_28.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_28.gif)

![ArrayPlotWithLegend_29.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_29.gif)

Test of the MapThread mechanism for the options:

![ArrayPlotWithLegend_31.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_31.gif)

![ArrayPlotWithLegend_32.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_32.gif)

![ArrayPlotWithLegend_33.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_33.gif)

![ArrayPlotWithLegend_34.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_34.gif)

![ArrayPlotWithLegend_35.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_35.gif)

![ArrayPlotWithLegend_36.gif](../../../assets/2017/05/28/ArrayPlotWithLegend-500px/ArrayPlotWithLegend_36.gif)

