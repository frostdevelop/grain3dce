# Grain3D v1.2
A (very cool) 3D rasterizer using TI-Basic\
Models are stored through a Matricies!
## Controls
KEY | Control
-- | --
Arrows | Rotate Camera
2nd | Up
del | Down
mode | Forward
stat | Right
apps | Backward
alpha | Left
y= | Toggle Text
## Model Format
Row | 1 | 2 | 3 | 4
-- | -- | -- | -- | --
1 | Row of Last Vertex | Row of Last Edge | Null | Null
2 to Last Vertex | X | Y | Z | Null
Last Vertex+1 to Last Edge | Vertex Row | Vertex Row | Color | Null
Last Edge+1 to End | Vertex Row | Vertex Row | Vertex Row | Color