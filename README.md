# pyglobe3d
PyGlobe3D is a free open-source logical-graphical Python library for creating globes by hexagon-like polygons and working with them. 

The surface units are mainly hexagon-like polygons consisting of six triangles and also tvelve additional pentagon-like polygons consisting of five triangles and lying only in the vertices of the icosahedron. They approximate the sphere or any part of the sphere. 

<img src="https://user-images.githubusercontent.com/85578981/127783633-d5dc5e1b-57e8-426b-ae48-cb57790e715e.png" data-canonical-src="https://user-images.githubusercontent.com/85578981/127783633-d5dc5e1b-57e8-426b-ae48-cb57790e715e.png" width="500"/>

Changing the radius of the sphere for any surface unit can create arbitrary 3D surfaces on the sphere. The logical component is that each surface unit knows its nearest neighbors-units that is performed algorithmically, not through storage.
