Program to analysis Hydrogen bonds in water simulation from GROMACS files.
It uses MDAnalysis: https://www.mdanalysis.org/

Returns the number of Hydrogen bonds and the average angles at given temperature.

python HBanalysis.py temp

where temp is the temperature at which the simulation is carried out.
The files should be in the following format: 'eq_' + temp + '.gro' and 'eq_' + temp + '.trr'