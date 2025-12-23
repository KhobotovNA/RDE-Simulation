This is a Sod verification test.To perform it follow classic instructions:
1) foamCleanCase
2) blockMesh + setFields + checkMesh
3) foamRun 
4) postProcess -time 0.003 -func -sample
This is an example for 4000 cells, if you want to perform a convergence study or visualize the results using my script.
Use the Sod_Conv(1).ipynb file. You also need to perform several studies with different number of cells for script.
