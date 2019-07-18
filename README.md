# D3R-GC4
Supporting Informatino data from 
Blinded prediction of protein-ligand binding affinity using Amber thermodynamic integration for the 2018 D3R grand challenge 4
Junjie Zou, Chuan Tian, Carlos Simmerling

File misc.xlsx contains 1) list of indexes corresponding to ligand IDs; 2) ligand IDs in each group as shown in Fig. 1; 3) initial state, end state and number of steps of each transition in Fig. 1; 4) calculated and experimental ∆G values. 5) raw data and figure for Fig. 6. 

File SI.docx demonstrates two examples at where softcore TI/dual topology approach in Amber are problematic. 

Folder input contains pmemd input files for conducting minimization, equilibration and production runs with λ=0.00922. Input files are the same for other λ windows except the clambda flag. 

Folder mol contains mol2 files for all ligands and substructures. 

Folder prm7rst7 contains all Amber parm7 and rst7 files for the TI calculations using pmemdGTI. 

Folder smile4sub contains the smile strings defining the substructures. 

Folder TIexample contains an example TI calculation for transformation of ligand 004 to substructure A.
