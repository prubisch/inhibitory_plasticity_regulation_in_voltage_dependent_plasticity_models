# inhibitory_plasticity_regulation_in_voltage_dependent_plasticity_models

This repository holds all code and data to reproduce the figures of the manuscript "The role of temporal sensitivity of synaptic plasticity in representation learning" (Rubisch et al., 2024) https://www.biorxiv.org/content/10.1101/2024.09.27.615415v3( (v1 was named "The trade-off between temporal precision and effect amplitude of inhibitory plasticity regulation determines separability of learned representations"). All notebooks can be executed without adaptation, given that BRIAN2 and its supporting packages are installed. 

The simulation data needed to plot Figures 3,5,6, and Appendix Figures 10,11,14 is stored in the directory */simulation_results*. 
The notebooks *EI_balance_frequency_dependency.ipynb*, and notebook in directories */bars_and_stripes*. */receptive_fields* provide the necessary code to reproduce the data. However, we do not recommend running them without the support of a computing cluster due to the long run time of the protocols. 

The produced figures will differ from the figures in the publication. Circuit diagrams and visual examples of the analysis have been added using Inkscape. SVG files are provided in */figures*.



