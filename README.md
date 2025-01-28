# Topology across scales on multiplexed data

This repository accompanies the manuscript "Topology across scales on multiplexed data", in which we analyse two sets of multiplexed images of tissue using persistent homology (PH).

## Contents
- Code of the analysis performed on the first data set: LUPUS murine spleen - topological data analysis.ipynb.
- Files with landmark points used for witness filtration: landmarks_red_pulp_file, landmarks_white_pulp_file.
- Files with pre-computed results to shorten the running time: stitched_file, witness_red_pulp_file, witness_white_pulp_file.

## How to use
The data we analyse was presented in https://doi.org/10.1016/j.cell.2018.07.010.
- Cell locations and annotations can be downloaded in https://data.mendeley.com/datasets/zjnpwh8m5b/1, file MRLdatasetexpression.csv.
- Translation between cell type names and number identifiers can be found in Table S2: https://pmc.ncbi.nlm.nih.gov/articles/PMC6086938/#_ad93_, file mmc2.xlsx.

To run the code, these two files need to be included in a folder named 'data' in the same directory as the python notebook.

List of required Python libraries: numpy, math, matplotlib, pickle, pandas, time, scipy.stats, sklearn, gudhi, persim, collections, warnings.
