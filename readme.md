# Timberline5

![](render.jpg)

The best way I've found to export the files so far is to open Blender, select the plate you want(Top, Bottom, Cam, Bottom Square, Arm), copy it into another instance of Blender, then apply all modifiers.

After that, you have to go into edit mode and remove ***all*** lines that traverse the inside of the geometry. Then, you need to scale the model down by $\frac{1}{1000}$ to get it from meters to millimeters. I use the "Import DXF" and "Export DXF" addons that ship with Blender to get output versions of my model. 
