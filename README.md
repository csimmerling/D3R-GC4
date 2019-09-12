# D3R-GC4
Supporting Information data from 

Blinded prediction of protein-ligand binding affinity using Amber thermodynamic integration for the 2018 D3R grand challenge 4

Junjie Zou, Chuan Tian, Carlos Simmerling

File misc.ods contains 1) ligand IDs in each group as shown in Fig. 1; 2) initial state, end state and number of steps of each transition in Fig. 1; 3) calculated and experimental ∆∆G values and the standard deviation of the calculated ∆∆G values from the three independent runs. 4) raw data and figure for Fig. 5. 

Folder 2d-sketch contains figures showing the 2d structures of ligands in Cathepsin S free energy data set. 

Folder input contains pmemd input files for conducting minimization, equilibration and production run with λ=0.00922. Input files are the same for other λ windows except for the clambda flag. 

Folder mol contains mol2 files for all ligands and substructures. 

Folder prm7rst7 contains all Amber parm7 and rst7 files for the TI calculations using pmemdGTI. 

Folder lib and folder frcmod contain library files and force field modification files used by Amber tleap. 

Folder pdb contains the pdb files loaded into Amber tleap for the protein-ligand complexes and the monomeric ligands. 

Folder smile4sub contains the smile strings defining the substructures. 

Folder prmLA contains Parmed scripts used for generating parm7 files for Amber TI. 

Folder TIexample contains an example TI calculation for the transformation of ligand 004 to substructure A.

