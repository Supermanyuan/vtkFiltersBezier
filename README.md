# vtkFiltersBezier

This is my project for Google Summer of Code 2015 VTK-CAD Model and Simulation Spline Visualization
[Link](https://www.google-melange.com/archive/gsoc/2015/orgs/vtk/projects/lin.html)

I added a vtkFiltersBezier module for spline visualization into VTK

1. vtkPatchInterpolation provides methods for point interpolation and triangulated mesh generation
2. vtkNURBSPatchAdaptor provides methods to convert NURBS patch to Bezier patch for visualization and some other basic algorithms like knot insertion, derivative evaluation and point inversion/projection
3. vtkBREPReader is a vtkAlgorithm to load .brep file and return triangulated mesh of the spline parts in vtkUnstructuredGrid
