# Italian-goat-breed-genomics
This repository accompanies the Erasmus dissertation:
"In-depth Genomic Exploration of Italian Goat Breeds Using Visual Analytics"

## Overview
This project takes a visual, data-driven exploration approach to understanding genomic differentiation between Italian Alpine and Saanen goats and Italian local breeds. Rather than testing predefined hypotheses, the interactive tool allows the user to explore the data directly observing population structure in the network, selecting breed groups of interest, and dynamically identifying genomic regions that differentiate them. The analysis uses genotype data from 1,071 animals across 33 breeds (Cortellari et al., 2021).

## Interactive Notebook
The full analysis is available as an interactive Marimo notebook:
https://molab.marimo.io/notebooks/nb_LPpUc1CkiuEgPqsCpvgw1J

# How to run
Click the link above to open the notebook - it opens in read-only mode by default

To interact with the tool, fork the notebook on Marimo by clicking the Fork button

Click the yellow ▶ arrow to launch it in Marimo environment

Click the grid icon (⊞) in the top toolbar to switch to dashboard view — this shows all panels side by side without the code cells

# How to explore
Start with the network (Panel 1):
Select a breed from the "Select by breed" dropdown — for example, selecting ALP highlights all Alpine animals and shows where they sit in the multi-MST network relative to all other breeds. 
Switch the "Colour by" option between breed and region to explore different patterns in the population structure.

Follow up in the SNP panel (Panel 2):
ALP and SAA are pre-selected as the focal group by default. The panel dynamically shows the top differentiating SNPs between the selected group and the reference group, ranked by Hudson FST and allele frequency difference. 
Change the comparison by selecting different breeds in the Group 1 and Group 2 dropdowns — the ranking updates instantly.

Use the SNP Feature Ranker to filter by chromosome or genomic region and adjust the number of top SNPs displayed.

Gene-level exploration:
The gene-level ranking table aggregates SNP-level results per annotated gene, showing maximum FST and maximum |Δfreq| per gene. This allows rapid identification of candidate genomic regions for biological follow-up.


Zahra Mohammadi
