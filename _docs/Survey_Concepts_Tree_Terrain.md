---
title:  "Survey Concepts for Tree and Terrain measures"
layout: page
permalink: /Survey-Concepts/
--- 

# Survey Concepts for Measuring with Total Station (TS)

## TS Position, Reference Points and Orientation

Select a proper place for TS. An open area is recommended. You should see Rover-prism with fixed coordinates or the required benchmarks and measured objects well. Notice that it is nearly impossible to rich the top of high trees if they are close to TS (it cannot shoot vertically). Measure such trees from other points. 

Before starting shooting, TS has to be oriented. At least three points are recommended for this. Either existing benchmarks with predefined exact coordinates or DGPS rover are required.  

If GPS/GSM signal is good, use Rover to orient the station (three points are recommended). Notice the error rate. An error of up to 5 cm is acceptable. Notice that with the prism, you can reach a few kilometers. Thus, try far areas visible from TS that possibly have a better signal.

If the GPS/GSM signal is no satisfactory, use benchmarks to orient TS. Thee or two (if TS is set up on a benchmark) benchmarks should be visible from TS. Measure the required benchmarks from Survey/StationSetup menu (see Totalstation_and_Rover_Survey.md). 


If the GPS/GSM signal is no satisfactory and benchmarks are not available, try to detect the nearest area with a satisfactory signal. Place TS somewhere in between of the shooting area and the base GPS station. Make sure you can see Rover (while it has a satisfactory error rate, which is up to 3 cm) from TS. Orient TS with Rover. Try to reach the closest area visible from the area of interest. Measure new benchmarks using the prism. 

## Shooting trees and terrain

You can measure trees in two separate processes: attribute and geometry gathering. Both can be conducted in any order, in a different time, and even from different TS position. By default, we recommend to, first, collect the attribute information and, second, the geometry. 

Attribute gathering means collecting a single XYZ geometry point and some attributes (e.g., label, diameter, species, etc.). It is a relatively fast process; we expect no more than three minutes per tree. This can be done in either reflector or reflectorless mode, but we recommend to use the reflector with a tablet to input all information standing near a tree.  A detailed description of the attribute gathering is provided here Totalstation_Tree_Attribute.md.

Geometry gathering means working in the reflectorless mode for collecting several points on a tree from bottom to top. It provides us a skeleton of a tree.  A detailed description of the geometry gathering is provided here Totalstation_Tree_Geometry.md.

The terrain can be reconstructed by combining the points collected in the reflector mode for the attribute gathering and extra points measuring specifically for the terrain surface. See detailed description here  Totalstation_Terrain.md. 

