# HIV_controllers_ATHENA
**Analysis of the survival and proteomic profiles of HIV controllers.**

**Contains the R code to produce the findings and figures of the following publications**
- Risk of Non–AIDS–Defining Events Is Lower in Antiretroviral Therapy (ART)–Naive HIV Controllers Than in Normal Progressors on Suppressive ART | doi: 10.1093/cid/ciae440
- Longitudinal Plasma Proteomic Signatures of Elite and Viremic Spontaneous HIV Controllers | Under review

## Additional notes
The code can be run on a single local machine without problems. Note that the code has not been optimized for computational efficiency. Although little effort was put in to avoid code duplication and to structure code into functions and objects, each code step is accompanied by explanations. This research problem is highly specific niche and requires a substantial amount of domain knowledge that only specialized doctors and the data collectors have. The attempt was made to document this specific knowledge in the notebooks. Note that the R code itself does currently not adhere to the DRY principle (Don't Repeat Yourself).

Note that these steps may take a few minutes on a typical local machine:
- the evaluation of influential observations (AthenaFullClinical_SurvivalModels_I)
- the interaction of covariates AGE & GROUP with TIME (AthenaFullClinical_SurvivalModels_I)
- Processing of Lues/Syphilis testing data (AthenaFullInfections_Cleaning)

Privacy laws and obtained consent did not allow to share the full dataset. However, cleaned mock data will be added that is very similar to the results of the publication, so that users may run the models themselves.

