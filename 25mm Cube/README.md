# 25mm Cube

Use to calibrate XYZ movements and extrusion multiplier.

1. Make sure to check that you extrusion multiplier is set to 1.0
2. Print a cube (eg. 40x40x40 mm) using the vase mode (Calibration cube STL)
3. Make three or more measurements of each wall and calculate the overall average thickness
4. In Slic3r go to Print settings - Advanced, here you can see the External perimeters width
5. **Extrusion multiplier = (External perimeters width / Average measured wall thickness)**
6. Change the Extrusion multiplier in Filament Settings - Filament=
