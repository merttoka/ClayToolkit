05/10/2024 (0.6.0)
========
- Cleaned up for GitHub

01/10/2024 (0.5.3)
========
- Added Tronxy Moore 2 Pro config
- Fixed bugs with non-Potterbot machines

08/23/2023 (0.5.2)
========
- Scara functions better integrated
- Added support for open toolpaths in basic slicer


08/15-16/2023 (0.5.1)
========
- fixed a bug with slicing meshes
- adjusted extrusion and clay use for small potterbot
- added Scara, Eazao, Lutum and Brutum profiles
- rewrote the gcode creation part in python. Limiting
the extrusion values to avoid exploding upto millions
- updated "center on bed" block, it now centers on 
a specific point (useful for Scara)
- added extrusion multiplier option for all printers. 
Auto-extrusion toggle can be usef for Potterbots.


08/4/2023 (0.5.0)
========
- added version and time to gcode files
- clay usage works with Mini and Super 
- adjusted multiwall distances


08/3/2023
========
- added multiwall support to slicer
- reorganized gcode save and visualization groups
- added an option for scaling only Z for gcode
reexport
- added multiwall support to reexporting the gcode


08/2/2023
========
- dimension visualization
- gcode import to change layer height and nozzle width
--- layer height change scales the object


07/31/2023
=========
- GH metadata saved with gcode file
- Layer and vertical patterns work with any integer now 
--- (0 disables patterning, anything else scales)
- image texturing for slicing
- [BUG] removed textures from rim layers


07/25/2023
=========
- multi wall support
--- option: wall printing order
- surface visualization for surface textures








