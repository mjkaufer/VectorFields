# VectorFields
A three.js app to visualize vector fields.

Live [here](http://www.kaufer.org/VectorFields/)! You can check out the 3D version [here](https://github.com/mjkaufer/3DVectorFields/)!

Set equations for the x and y components of the vector field using variables `x` and `y`, representing the location of the point in the coordinate system, along with `t` representing elapsed time. You can also use any JavaScript math function, such as `Math.sin`.

There's also an option to plot a shape as it deforms in the vector field over time. `x`/`y` length control the length of that shape. You can set the amount of cross-sections to deform (more cross sections = more CPU intensive). The rest of the settings are self explanatory.

I don't visualize the magnitudes of the vectors because it would get real ugly real quick.  
