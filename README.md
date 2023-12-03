[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12184677&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group 13 - Improvement on yanuthone D production in Aspergillus niger

## Project Summary 
The project endeavors to engineer and refine a cell factory for the production of the medically significant antibiotic, "yanuthone D." Aspergillus niger was selected as the cell factory of choice due to the native presence of yanuthone D's pathway in its metabolic repertoire. The application of Flux Balance Analysis (FBA) using the Python package "Cobrapy" facilitated the investigation. Medium optimization identified a potential enhancement in product yield through precursor addition. Phenotype Phase Plane (PPhP) analysis uncovered crucial metabolic behaviors impacting oxygen availability in product formation, further corroborated by Dynamic Flux Balance Analysis (DFBA). Flux scanning based on enforced objective flux (FSEOF) and Optknock analyses suggested a set of target reactions, forming the basis for the hypothesis that mevalon synthesis constitutes the bottleneck in yanuthone D production. The insights from FSEOF, Optknock, and PPhP analyses led to the proposition of a strain with optimal performance for yanuthone D production. DFBA analysis served to validate these hypotheses.

## Project Overview
The project is organized into two main sections: the analysis and the report. 

The report can be found in the Jupyter Notebook "**Report.ipynb**" and provides information on the compound of interest and the  cell factory used, as well as on the model that has been utilized to perform the analysis. The report contains a throughout explanation of how and why the analysis was performed. 

The analysis can be found in the folder "**Analysis**", which contains seven subfolders, each containing a different analysis. Computations have been performed on:
- **Maximum theoretical yields**: Theoretical yield calculation 
- **Model Optimization**:  Medium formulation, Carbon source optimization, Potential precursor testing
- **Model comparison**: Model reliability & consistency assessment 
- **Model pathway validation**: Pathway of interest validation in GEMS 
- **Phenotypic phase planes**: PPhP analysis
- **Predicted genes for manipulation**: FSEOF, Optknock, Manually derived engineered strain simulation
- **DFBA**: DFBA analysis

Details on the requirements for this project can be found in **requirements.txt.** 
