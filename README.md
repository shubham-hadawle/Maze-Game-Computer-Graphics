# Maze-Game-Computer-Graphics-
A Maze Game created using Computer Graphics in C++

The project is about implementing The Maze Game in the First- Person view. For this we use the various concepts such as two- dimensional viewing transformations, clipping projections, visible surface detection, animation etc. learned throughout the course of our subject.

The maze is described as a 2D structure assumed to lie in the XY plane.

A maze consists of rectangular cells separated by edges. The edges may be either transparent or opaque. The viewer is supposed to see through transparent edges into the neighbouring cells, and they should not see-through opaque edges. The edges are assigned a color (which is meaningless for transparent edges). We can also convert the maze into 3D. For this we need to extrude each edge vertically from the floor to the ceiling to make a wall. The floor is
at z=0 and the ceiling are at z=2. Each wall should be drawn with its assigned color.
Associated with the maze is a viewer. The viewer has an (x, y, z) location. For the project, the viewer is always looking horizontally, never upward or downward (or, always parallel to the floor or ceiling). This means that, after perspective projection, the left and right edges of walls are always vertical. In turn, this allows us to do all the visibility working with lines in 2D, before we extrude the walls.
