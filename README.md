# prediction_project_design_framework
How to design Prediction Project?

- What are we trying to predict? (-> Prognosis or Diagnosis?)
1. Prognosis -> Watch out for HTE (consider counterfactual predictions)
2. Diagnosis -> Wath out for referal/workup bias (consider multiple imputation, exoganouse prevalence etc)

- What will we do with the predictions? (-> Are you worried about Treatment Harm or Resource Constraint?)
1. Avoide Treatment Harm -> Define cost of treatment harm and use NB (Calibration is important and affects NB)
2. Deal with resource constraint -> use flexible Lift Curve / PPV values for different PPCR (Discrimination Performance Metrics)

- What is hapenning today? (-> Which current strategy are you trying to beat? Treat All? Treat None? Baseline Model?)
1. Treat All / Treat None / Formal Tree Models.
