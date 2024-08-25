This directory contains the data and code used in the simulation experiments for PITCH.

In the `data` folder, you will find the following for four types of cancer:
- Mutation data (`TCGA-****.htseq_counts.txt`)
- Gene expression data (`****_mc3_gene_level.txt`)
- Integrated pathway information (`kegg_pathways_aggravated.txt`)
- PPI data (`STRINGv10.txt`)

In the `reference gene list` folder, there are the `general_driver_list.xlsx` for comparison and the reference gene lists for each of the four types of cancer.

In the root directory, the `Main.mlx` file contains the core algorithm of PITCH, while the remaining files are the code used for calculating relevant metrics. For better visualization, we used Origin Pro to plot the data generated by `3_ActionableAndDruggable.mlx`.
