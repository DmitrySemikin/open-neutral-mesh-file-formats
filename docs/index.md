---
permalink: /
---

# About

Main goal of this project is to define several file formats, which could
be used for easy and efficient exchange of meshes between different SW
packages. In context of this project the word mesh means discretisation
of geomtrical objects, like in FEM or FVM.

The following file formats are planned to be developed:
* Triangular mesh (effectively it is intended to be a replacement
  for stl)
* Tetrahedral mesh (special case of linear mesh below). It is 
  not yet clear if separate format is needed for this kind
  of mesh.
* Linear mesh. Can represent linear surace or volume elements,
  like tetrahedron, wedge, hexagon, prism etc., but not generic
  polyhedral mesh.
* Polyhedral mesh. Often used in CFD applications. Usually uses
  different topology definition compared to the linear mesh
  above.

Each of the formats above should be defined in two variants:
text and binary.

As further development one may consider also definition of
additional format(s) for representation of non-linear elements.



## Further information

[Project wiki](https://github.com/DmitrySemikin/open-neutral-mesh-file-formats/wiki) 
contains further information about the project,
its objectives and goals.

Currently the specification of Neutral Triangular Mesh format
(text variant) is work in progres. 
[Draft of the specification](https://github.com/DmitrySemikin/open-neutral-mesh-file-formats/wiki/neutral-triangilar-mesh-text-v1)
of this format is available in Wiki as well as 
[page devoted to the rationale](https://github.com/DmitrySemikin/open-neutral-mesh-file-formats/wiki/neutral-triangular-mesh-text-reasoning)
for the decisions made in the specification.

Please, don't hesitate to ask question or share your thoughts
about this format in the 
[Discussions](https://github.com/DmitrySemikin/open-neutral-mesh-file-formats/discussions) 
section.
