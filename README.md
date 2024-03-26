# Liquefaction-gravel-eml-2023
This repository is for explainable/interpretable model to assess gravelly soil liquefaction potential. The DPT-Vs database is used to develop the model. This model is developed by using LightGBM and SHAP.

This repository contains these files: processed dataset, a csv file containing IPs of test sites, and a python script. 

This repository is part of the below project. If you use this in your work, dont forget to cite as below:

Jas, K., Mangalathu, S., & Dodagoudar, G. R. (2024). Evaluation and analysis of liquefaction potential of gravelly soils using explainable probabilistic machine learning model. Computers and Geotechnics, 167, 106051. https://doi.org/10.1016/j.compgeo.2023.106051. 

Diect link to this article: https://www.sciencedirect.com/science/article/pii/S0266352X2300808X?via%3Dihub. 

Researchgate paper link:
https://www.researchgate.net/publication/377261175_Evaluation_and_analysis_of_liquefaction_potential_of_gravelly_soils_using_explainable_probabilistic_machine_learning_model. 

You can request full text. Read and recommend also.

In case any queries about this work, feel free to contact with this email id: ce19d202@smail.iitm.ac.in. // kaushik.jas.2013@gmail.com

# Data and Code Availability Statement

Name of the code: Gravel_EML_KJSMGRD_23.

Developer name: Mr. Kaushik Jas. 

Contact address: Department of Civil Engineering, Indian Institute of Technology Madras, Chennai, Tamil Nadu 600036, India.

Email: ce19d202@smail.iitm.ac.in. 

First available year: 2023

Program language: Python 3.7; MATLAB R2022b

Downloadable link of source code: https://github.com/Kaushikjas10/Liquefaction-gravel-eml-2023.git 

# File descriptions (Beta version)

(1) [Processed dataset]: It is available with the article in the supplemental material at "Appendix A". The file is now available in this repository as file name "Jas et al. 2024_Supply_EML_Gravel_Liq_COGE.pdf".
This is the same dataset used for the model training and testing. This same file is attached to the COMGE journal section.

(2) [TestSitesGravel.csv]: This is the  spreadsheet template of the test sites where you want to assess the liquefaction potential of gravelly soils using the developed model.

(3) [MODEL B_Liq_KJSMGRD.json; MODEL B_Liq_KJSMGRD.txt]: These are the LightGBM model files with two different extensions. This file can be loaded in the Python platform to predict the liquefaction potential assessment of gravelly soils for site(s) of interest having all IPs in a excel spreadsheet. Also you can find the model details/parameters (Table 5) in the manuscript itself. 

(4) [Model_Train_Test_KJ_SM_GRD.ipynb]: This Python script is provided to give a demonstration for using this model in the jupyter notebook platform.

(5) Interactive online tutorial: Will be uploaded soon....................

### Release notes:
Update 26-03-2024: 1)All the necessary files are uploaded except (2) and (5). Those files will be uploaded soon..........
