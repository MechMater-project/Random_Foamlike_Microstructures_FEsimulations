# Random_Foamlike_Microstructures_FEsimulations
Netgen geo files for random porous microstructures like foams are distributed here.
These files can be loaded and mesh with Netgen GUI. 

The microstructures have been build by shrinking Voronoi volumes obtained from randomly distributed seed points in a unit cube.
Building procedure is provided in 

[1] T. Merlette, J. Diani, 2025. 3D finite element investigation of hyperelastic foam behavior. I. Voronoi closed-cell microstructures, Mechanics of Materials, 105566.
https://doi.org/10.1016/j.mechmat.2025.105566

These microstructures have been used for severe compression, up to 95%, by finite element simulations.
The explicit Abaqus input files for uniaxial compression are also available. 

The nomenclature is the following Voro80-11_008_922
- Number of pores 80
- label of the micrsture 11
- maximum length of elements 0.008 knowing that the cube is of length 1
- Porosity 92.2%

Please cite [1] and the github link if you use some of these files.
STL and Abaqus input files are too large to be shared here. You may contact the authors.
