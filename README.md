# On the role of barotropic versus baroclinic dynamics in generating a Taylor Cap at Maud Rise, Weddell Sea

*Authors: Birte Gülk, Fabien Roquet, David Ferreira, Alberto C. Naveira Garabato

This repository presents the used model set-up and scripts for generating the forcing files used for the idealizied MITgcm configuration, and contains the scripts for analysing the model output in the paper which is submitted to JPO.

# Content

- MITgcm setup
 This folder provides the MITgcm settings for reproducing the 25km (subfolder dx_25km) and 5km (subfolder dx_5km) resolution runs.
 The binary fiels for the bathymetry, temperature stratification and open boundary conditions for the 25km horizontal resolution case are computed by "generate_input_caseABCD.ipynb" and "generate_realisticcase.ipynb" and for the simulation using the 5km horizontal resolution by "generate_input_caseC_HR.ipynb".
 
- Analysis and figures
This folder provides the python scripts to analyse and create the figures presented in the paper. 
