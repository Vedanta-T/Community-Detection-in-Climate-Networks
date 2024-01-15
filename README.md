This repository contains the code involved in the special topic done for the course C5.4 Networks as part of the MSc. in Mathematical Modelling and Scientific Computing at the University of Oxford.
The 4 files use data sourced from the NCEP-NCAR Reanalysis 2 project, the data file required for each notebook is mentioned at the top of the respective file.

Each notebook creates a climate network based on a certain field namely the Surface temperature, Geopotential height and Mean sea level pressure. The code then constructs the network based on specified threshold and
conducts a community detection analysis. The final output of each notebook is a communities object which contains the information of the communities detected and also returns a plot of the communities on a geospatial
grid.
