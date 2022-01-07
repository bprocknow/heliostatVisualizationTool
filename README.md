# heliostatVisualizationTool

  This is a visualizing tool to simulate a heliostat system that can move around
  in a 3D plane.

  Matrix/Vector nomenclature:
  Local Axis:  Are the blue (Z), green (X), and red (Y) axis's that define
  the heliostat itself.  These move with user inputted rotations (see below)

  Absolute Visual Vectex:  The white axis, that are absolute relative to the user

  Heliostat vertex:  These are to the heliostat (rectangle) itself.

  Input Buttons:
  q,w: Rotate around the local X axis
  a,s: Rotate around the local Y axis
  z,x: Rotate around the local Z axis
  e: Rotate -90 around the local X axis:  I recommend using this as soon as the
      screen starts to orient the Z in the up direction (towards the sky)
  -,=: Zoom out, in
  g,h: Turns on/off the ground (green) and the sky (blue)
  r: turns on/off sun rays
  p: Turn on/off the tracking algorithm

## Usage

pip install pygame
pip install numpy
pip install PyOpenGl

python helioVis.py
