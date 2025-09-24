# NREL 15-MW TLP Input File Set

This folder contains NREL model input files for a tension-leg platform (TLP)
design for the IEA Wind 15 MW reference turbine [1]. The TLP design includes 
variations for water depths ranging from 200 m to 1500 m. 

More information about the design and how it was developed can be found in

  M. Hall, S. Housner, L. Carmo, "A Reference Tension-Leg Platform for a 15 MW Floating Wind Turbine," 
  Proceedings of the ASME 44th International Conference on Ocean, 
  Offshore and Arctic Engineering, DOI: [10.1115/OMAE2025-157544](https://dx.doi.org/10.1115/OMAE2025-157544), NREL/CP-5000-93911, 2025.

### Provided files

Input files for frequency-domain modeling in 
[RAFT](https://github.com/WISDEM/RAFT)
are provided for the full range of water depths. Users can select the
appropriate files for their water depth of interest.

Input  files for time-domain modeling in 
[OpenFAST](https://github.com/OpenFAST/openfast) 
are provided for the water depth of 800 m. These input files currently
are set up for OpenFAST v4.0.3. Experienced users may use
RAFT to compute the necessary OpenFAST inputs for the designs at
other water depths. Input files for other water depths or newer OpenFAST
versions may be posted in future.

See [2] for a full description of the depth-dependent design variations.

### Comments and known issues

As with many existing reference floating wind turbine designs, this design 
has limited structural detail and did not go through 
a complete loads analysis. Within the limits of the existing definition, 
there is a suspected shortfall in fatigue life along the central column,
where the braces intersect, and at the top of the tower (the tower is the
pre-existing IEA Wind 15-MW floating tower design). These findings were
made by collaborators at IFPEN. Future design revisions may address these
issues.

### References

[1] E. Gaertner et al., “Definition of the IEA 15-Megawatt Offshore 
Reference Wind Turbine,” NREL/TP-5000-75698, 
2020.

[2] M. Hall, S. Housner, L. Carmo, "A Reference Tension-Leg Platform for a 15 MW Floating Wind Turbine," 
Proceedings of the ASME 44th International Conference on Ocean, 
Offshore and Arctic Engineering, 
DOI: [10.1115/OMAE2025-157544](https://dx.doi.org/10.1115/OMAE2025-157544), 
2025.

