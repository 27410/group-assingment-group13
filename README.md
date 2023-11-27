[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12184677&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/[PUT-YOUR-REPOSITORY-HERE]/main)

# 27410 - Group assignment - Group 13 - Improvement on yanuthone D production in Aspergillus niger

> Dear students, thank you for accepting the group assignment. Please fill in the
> requested information below and above ([Group Number] and [TITLE]) and remove this quoted part before submission (everything prepended with a >).
> Please also replace `[PUT-YOUR-REPOSITORY-HERE]` up in the first line 👆 with the name of your repository here on GitHub.
> That way someone can click on the Binder badge icon and open your project in Jupyter lab to explore it.
> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)
The aim of the project was to design and optimise a cell factory to produce the medically important antibiotic "yanuthone D". The chosen cell factory was A. niger because yanuthone D's pathway is native to *A. niger*. Flux balance analysis (FBA) was performed using the python package "Cobrapy".

## Project overview
The project is organised into two main sections: the analysis and the report. 

The report can be found in the jupyter notebook "Report.ipynb" and provides information on the compound of interest and the  cell factory used, as well as on the model that has been utliized to perform the analysis. The report contains a throughout explanation of how and why the analysis was performed. 

The analysis can be found in the folder "Analysis", which contains six subfolders with each of them containing a different analysis. Computations have been performed on:
- Maximum theoretical yields
- Model optimization
- Model comparison
- Model pathway validation
- Phenotypic phase planes
- Predicted genes for manipulation 

Details on the requirements for this project can be found in requirements.txt. 