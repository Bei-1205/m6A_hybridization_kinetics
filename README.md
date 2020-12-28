# m6A_hybridization_kinetics
 
### CEST simulation, kinetic simulation and prediction source code for m6A excited states paper

### This is all the CEST/Kinetic simulation and prediction source code files for the m6A Excited states paper
### Ref: Liu et al, (2020) "A quantitative model predicts how m6A reshapes the kinetic landscape of nucleic acid hybridization and conformational transitions" BioRxiv
###
### 1. m6A_Kinetic_Simulation (python 3.6)
### folder containing all kinetic simulation code
#### a. Vant_hoff_extrapolation.ipynb
####  Tempareture dependent R1p/CEST mesurement of methyl isomerization in m6AMP, ssRNA and dsRNA
#### b. Final_kinetic_simulation.ipynb
####  4-state simulation kinetics simultaion and m6A apparent kon, koff prediction, genome wide m6A DNA kon prediction
#### c. Genome_wide_DNA_kon_prediction.ipynb
####  generate 12-mer DNA sequences containing m6A from mouse genome. predict dG and kon for the unmethylated DNA sequences
#### d. TAR_ES_Simulation_final.ipynb
####  Kinetic simulation for methylated TAR conformational transition
###
### 2. CEST_4state_simulation (python 3.6)
#### a. 4state_CEST_simulations.ipynb
####  4state CEST simulation code
#### b. C2_55_4state.txt
####  a text file containing exchange parameter inputs for dsGGACU m6A6-C2 CEST simulation
#### c. 4state_template.txt
####  a template for exchange parameter inputs
#### d. dsGBCm6A_m6A6C2_55C.csv
####  experimental dsGGACU m6A6-C2 CEST data containing RF powers and offsets
###
### 3. CEST_4state_fit (python 2.7)
#### a. 4state_fit_v3.py
####  python script used for 4state fitting, the command is "python 4state_fit_v3.py BMNS_params_global.txt fit_output"
#### b. BMNS_params_global.txt
####  text file containing the fitting inputs
#### c. dsGBCm6A_mA6C2_55C.csv and dsGBCm6A_mA6C8_55C.csv
####  experimental data from CEST measurements to fit
#### d. fit_output
####  out put file of the fitting program
