# Coonspatch-python-blender

Using Blender Scripting functionality Coons patch is implemented. The coordinates (X,Y,Z) of control points of four Bezier curves is read from the file 
coons_patch_points.txt . Each line 4 lines contains the control points of a Bezier curve. The first and third lines are the coordinates of the start and 
end points of the curve, and the second and fourth lines are the coordinates of the two handle points. These four sets of control points determine the 
boundary of your Coons patch. After you load the points from the files you should generate the Coons patch based on the method discussed in the class and 
render it in Blender.

The following is the result of coons patch from four bezier curves.
![output.png](ouput.png)
