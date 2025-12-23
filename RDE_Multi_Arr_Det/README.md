This is a main case for my project. It is a 3D RDE simulation via MulticomponentFluid. This exact case is for 100K cells, that I usually use for tests and on 1 core run. The procedure for start is usual for my cases:
1)foamCleanCase
2)rm -r 0 + cp -r 0-2.orig 0
3)blockMesh + setFields + checkMesh
4)foamRun
For MPI run on finer mesh follow the mesh descriptions on the Final Report. 

