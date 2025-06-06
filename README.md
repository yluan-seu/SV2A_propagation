The code SV2A_propagation_simulation.Rmd with simulated data and processed can be run to replicate the major analyses of the article:
Luan et al., Synaptic loss pattern is constrained by brain connectome and modulated by phosphorylated tau in Alzheimer’s disease

System requirements:
MacOS or windows workstation running RStudio
All the code was tested on RStudio Version 4.3.1 on MacOS Ventura 13.5 with a 3.6 GHz 10-Core Intel Core i9 processor and AMD Radeon Pro 5500 XT 8GB GPU

Installation guide & Demo
Install RStudio software and open the code "SV2A_propagation_simulation.Rmd"
Set the path to the Python interpreter under the virtual environment or Conda environment with reticulate package.
Install "netneurotools" and "neuromaps" toolboxes by "reticulate::py_install" function if necessary.
Store "simulation_rmd/schaefer200x7CommunityAffiliation_corrected.txt" under specific folder and load it.
Expected run time is about 30 minutes on MacOS Ventura 13.5

An example output in html format is shown in the file "SV2A_propagation_simulation_example_output.html"

