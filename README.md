# Callus-culture-isotope-labelling
Scripts and batch files for analysing isotopic labelling in  Aconitum plicatum callus culture metabolomics



This repository contains the MZmine batch files and a Python script used to analyse the results from callus culture feeding experiments with isotopically labelled ethanolamine and ethylamine. The workflow includes data preprocessing in MZmine and post-processing in Python to assess the incorporation patterns of labelled substrates in metabolic features. The files were used in a computational metabolomics pipeline applied to LC-MS data from Aconitum plicatum callus cultures.

Provided files include:
1. MZmine batch file for detection of all the features from the LC-MS analysis - where each isotope peak should be recognized as an individual feature.
2. MZmine batch file for subsequent SIRIUS analysis, necessary for classifying the detected metabolites.
3. Python script used to generate a final table of all the features classified as "Terpenoid alkaloids" by SIRIUS that show the incorporation of isotopically labelled ethanolamine and/or ethylamine.

![SI-workflow-computational-metabolmoics](https://github.com/user-attachments/assets/deb2d05e-4543-410b-9a7e-7f1f441063df)
