# TCGA Capstone Project - AEN in STAD
I will be using my assigned gene to see whether it is more active, less active or unchanged when the TP53 gene encoding the regulatory transcription factor p53 is mutated/inactivated in my assigned cancer type. 
Gene = AEN.
Cancer type = Stomach Adenocarcinoma.

# How to run the notebooks
Open each notebook in Google Colab and run each cell in order. The notebooks use Python with added NumPy, Pandas, Matplotlib and SciPy libraries. To run each cell, select runtime in the menu bar and run all:
NOTEBOOK 1 = Run all cells to clean the phenotype data, summarise and make checks.
NOTEBOOK 2 = Run all the cells to summarise expression across each cancer type, compare all groups, plot figures, make checks and run a complete analysis.
NOTEBOOK 3 = Run set up cells and cells inside option A to compare expression deleted and nondeleted TP53 wild-type tumours 

# One sentence answer
In STAD, AEN expression was lower in TP53 mutant tumours compared with TP53 wild-type tumours (median difference = -0.330 log2 units, ~20% lower, p = 3.54 x 10^-5), which is suggestive of a gene activated by functional p53. 
