## Structure-to-Function Analysis of Maize C1A Papain-like Cysteine Proteases (PLCPs)

Authors: Haimantika Dey, Vaishnavey SR 


### 📌 Overview
This repository contains analyses, data, and scripts from a study investigating how sequence and structural variation in maize C1A papain-like cysteine proteases (PLCPs) influence substrate specificity and thermal stability. PLCPs (MEROPS family C1A) are thiol-dependent endopeptidases with critical roles in plant growth, programmed cell death, immunity, and stress tolerance.

### 🎯 Key Objectives
Evolutionary Structural Mapping: Aligned PLCP structures to identify conserved catalytic and pro-domain residues linked to enzymatic efficiency.
Mutational Landscape & Stability: Assess single-point mutants using PyRosetta energy minimization to predict stability and turnover-enhancing variants.
Ligand-Binding Predictions: Use Boltz-2 scoring to compare substrate-binding affinities of wild-type and mutant structures.

### 📂 Repository Structure
To be updated

### 🧪 Methods Summary

Structural Dataset: 11 experimental PDB entries + ~260 AlphaFold2-predicted structures for MEROPS sequences.
Alignment: FoldMason MSA for structural alignment and residue mapping.
Pocket Analysis: CASTp and fpocket for active-site geometry characterization.
Stability Analysis: PyRosetta energy minimization for wild-type and mutants.
Binding Predictions: Boltz-2 scoring for substrate affinity differences.


### ✅ Major Findings

Conserved catalytic and pro-domain residues mapped across PLCPs.
Identified mutants predicted to reduce stability or enhance turnover.
Substrate-binding trends differ between wild-type and selected mutants.


### 🔄 How to Reproduce

Set up environment:
Install Python (≥3.8), numpy, pandas, biopython, mdtraj, PyRosetta, FoldMason, and Boltz-2 client.


Download structural data:
Refer to slides/pdb_list.csv.


Run alignment:
Shellbash scripts/run_foldmason_alignment.sh data/structures alignments/Show more lines


Energy minimization & scoring:


Prepare Boltz-2 inputs:
ShellShow more lines
Generate figures & analyses:

