## This code (plotWing.ipynb) defines a function "plotWing", and uses plotly to create a 3D delta wing model.
  - The delta wing has a NACA0012 cross section. 
  - On the surface, there is a triangle region that shows a pressure map, which is interpolated by "griddata" function, and the pressure data comes from 15 pressure ports. These 15 pressure ports are also shown on the surface.
  - The two pink cycles are ploted in inkscape. Although this can be done in python, it is really convenient to do that in inkscape.
  - I will upload the CP_plot_map.csv file once I finish my project.

![this is the link of the figure](https://github.com/general-chen/Python/blob/392f00575ead6e11b8d3fa715f8bb7adb46fe091/plot_3d_wing_add_map/deltawing_noFilter.png)

## This code contains many useful information of the function "plotly":
  - how to plot multiple elements in one figure (in my code, there is a 3d delta wing, a triangle pressure map, 15 scattered points).
  - how to set the camera, to make the scene in the right way.
  - how to save the interactive plotly figure as svg.
  - how to set surface color and color scale.
  - how to set color bar, the tracks of the 3d scattered points.
  - how to add text to the figure using annotations.
  
If you use plotly to plot 3d figures, my code is really a good reference.
