
I extracted the logo from 'ModLab Logos 1 Sheet.svg'

Logo-Outlines.svg - Just contains outlines of the logo elements.

The outline path isn't closed (open just above the B), so I closed it, and
removed an extraneous path at the end of LAB, and broke apart all of the paths
so that the inside of the O was separated from the outside of the O.


Logo-Outline-Faces.fcstd - Imported into FreeCAD

This imported the .svg file into FreeCAD, and converted all of the outlines to
faces, and then differenced the letters with their interiors. I then combined
all of the faces for the letters, so you wind up with 3 elements:
1 - The outline
2 - The claw
3 - The letters


Logo-Depressed-Lettering.fcstd - Extruded with depressed lettering

This extruded the outline -1.4mm, and then extruded the claw and letters by
-0.8mm and subtracted from the outline.


Logo-Depressed-Lettering.stl - Exported STL file from the fcstd file.

Note: This is quite large, and it is expected that you should scale this in 
the X & Y dimensions (Z is ok)


Logo-Depressed-Lettering-4up.stl

A 4-up of the logo scaled by 30% in X & Y.


Logo-Raised-Lettering.fcstd - Extruded with raised lettering

This extruded the outline -0.6mm, and then extruded the claw and letters by
0.8mm and unioned with the outline.


Logo-Raised-Lettering.stl

Note: This is quite large, and it is expected that you should scale this in 
the X & Y dimensions (Z is ok).


Logo-Raised-Lettering-40pct-1up.stl

A 1-up of the logo scaled by 40% in X & Y.


Logo-Raised-Lettering-4up.stl

A 4-up of the logo scaled by 30% in X & Y.

