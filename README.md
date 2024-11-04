# GH_Python_Distance-between-point-and-cubes
This script generates a grid of boxes in Grasshopper, assigns each box a color based on its position, and "bakes" (adds) the boxes to the Rhino model if the `bake` input is set to `True`. The code also includes error handling to ensure `eX` is an integer and takes care of context-switching between Grasshopper and Rhino to properly add the geometry.
