This is the Github repository for the manuscript entitled "Status Exceptions and Misalignment of Medical Urgency in U.S. Pediatric Heart Transplantation." The files required are the Q2 2025 version of the OPTN Standard Transplant Analysis Files. These data must be obtained through a data use agreement with the OPTN, which may be obtained after showing proof of IRB approval and submission of a project proposal to the OPTN. 

In order to run the code, please start with the file "data_cleaning_and_table1.Rmd." This RMD lists the standard analysis files that are required to run the code. Furthermore, this creates the final dataset of 6,026 candidates in our cohort along with the longitudinal dataset with 82,206 waitlist observations that is the basis for all of our time-varying mixed-effects Cox proportional hazards models. This document also provides code for Table 1 and Supp Figure 1, which describes the distribution of the patient volumes by transplant center.

The "cox_models.Rmd" document provides all of the code for developing Primary Models 1 and 2. It also provides separate code chunks for our model testing. The document also includes all code necessary for supplemental analyses 1-3 as described in the methods section of the paper. The main figures that are created using this document are Central Illustration, Supp Figure 1, Supp Figure 2, Supp Figure 4, and Supp Figure 5.

The "logistic_regression.Rmd" file provides all code necessary for recreating our mixed-effects logistic regression model studying factors associated with exception receipt as well as assumptions testing that we performed to ensure the robustness of the model. This document creates Figure 4 and Supp Figure 9. 

The "cumulative_incidence_setup_plots.Rmd" file provides all code necessary for the development of our cumulative incidence plots and performing Fine-Gray analyses. This document creates Figures 1 and 2. 

The "nhrb_analysis.Rmd" file provides the code necessary for reproducing our analyses of the NHRB, including a model that tests the interaction between the NHRB and exceptions as well as a graph that shows the percentage of transplant recipients with active exceptions. This file is necessary for producing Figure 3, Supp Figure 7, and Supp Figure 8. 

Lastly, the "cindex_time_dependent_auc.Rmd" file produces the code for the dataset that compares the actual and hypothetical system without exceptions. Code for producing the c-indices, the boostrapping, and the time-dependent AUC plots is present here. This file produces Figure 5. 
