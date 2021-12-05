# CausalSemiCompReproduce
Reproducibility of numerical examples and of simulation results associated with the paper "Causal inference for semi-competing risks data" by Nevo and Gorfine (2021+, Biostatistics). Comments and suggestions are welcomed and can be sent to 
danielnevo :panda_face: @ :panda_face: gmail.com (remove the pandas).

This repository includes two main parts
1. Simulations: Simulation scripts, simulation results and simulation summary.
2. Exact numerical examples for large sample (Figures 2 & 3 in the paper).

## Simulations
The two relevant folders are **Nonparametric** and **Semiparametric**. Within each folder there are three sub-folders and one script that was used for designing the chosen values.

1. **R**: Includes the scripts that were used to run the code. The code was ran on a cluster, and each simulation setup (different parameters and censoring rates) was written in a different **R** script. To speed up the simulations, ten scripts were ran simultaneously, and the code also uses parallel computing to run the bootstrap.

2. **Results**:  These RData files organized in subfolder with the names being the orignal **R** script names.

3. **Summaries**: With relevant folders. Simulation tables and figures can be recreated from the files in this sub-folder.

## Exact numerical examples 

Recreating Figures 2 and 3 in the papers. The folders include both simulation of very very very large populations, and then calculating the true causal effects in these populations, before creating the relevant figures.

