This is code working on Pylith to produce displacement and stress/strain in the ETSZ. 

The important steps to reproduce the result are: 

pylith east_tn.cfg

First, you need to install pylith, which is a package you could find in the following link:

https://geodynamics.org/cig/software/pylith/

The structure tree here are :

Mesh-------------Mesh folder

Mesh generation trelis journal file-------------Mesh_trelis

Result-----------Output_result

Spatial database-------------------spatialdb

input file-------------------------east_tn.cfg

input file 2-----------------------pylithapp.cfg



