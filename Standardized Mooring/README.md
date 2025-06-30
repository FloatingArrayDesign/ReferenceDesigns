# Standardized Mooring Designs

This folder contains input files for two floating wind farm mooring systems--
one for a Humboldt Bay lease area and one for a Morro Bay lease area. The 
mooring systems are standardized within each array to use a minimal number
of component sizes, with the goal of support mass manufacturing and ease of 
installation, maintenance, and replacement for large-scale floating wind 
projects.

Each design consists of 40 floating wind turbines (the IEA Wind 15 MW turbine [1] 
on the VolturnUS-S semisubmersible platform [2]) and their mooring systems.
The designs consider the
bathymetry and an approximation of the soil characteristics of the site, 
drawing on previous site condition information [3]. The Humboldt Bay designs are
based on three-line mooring systems (though some lines are doubled up to avoid
chain size limitations). The Morro Bay designs use six-line mooring systems.

Each turbine's mooring system is sized to approximately withstand site-specific 
extreme and fatigue loads using an interpolation procedure; the performance of
each mooring system has not beeen checked individually and is not assured. The
focus of this work is to compare supply chain implications of different mooring
designs at the array scale.

The designs are provided in the YAML file format of the Floating Wind Array 
Ontology, which is explained [here](https://github.com/IEAWindTask49/Ontology).
In addition, configuration and mooring-component input files are provided
for the [ORBIT](https://github.com/WISDEM/ORBIT) cost and logistics model, 
which models the supply chain demand of the designs.



[1] E. Gaertner et al., “Definition of the IEA 15-Megawatt Offshore Reference Wind Turbine,” NREL/TP-5000-75698, 2020.

[2] C. Allen et al., “Definition of the UMaine VolturnUS-S Reference Platform Developed for the IEA Wind 15-Megawatt Offshore Reference Wind Turbine,” NREL/TP-5000-76773, 2020.

[3] M. Biglu, M. Hall, E. Lozon, and S. Housner, “Reference Site Conditions for Floating Wind Arrays in the United States,” NREL/TP-5000-89897, 2024.

