# prediction_project_design_framework
How to design Prediction Project?

- What kind of Problem are we trying to solve?

We want to avoid op fractures with reccomendations, which patients are most likely to benefit?
(Too many diabetic patients, undiagnosed patients with HCV...)

- What are we trying to predict (Diabetes in 5 years, existing HCV, CKD in 5 years, OP, Lung Cancer)?
-> (is it a case of Prognosis or Diagnosis?)
1. Prognosis -> Watch out for heterogeneous treatment effect (consider counterfactual predictions)
2. Diagnosis -> Wath out for referal/workup bias (consider multiple imputation, exoganouse prevalence etc)

- What will we do with the predictions? (-> Are you worried about Treatment Harm or Resource Constraint?)
1. Avoide Treatment Harm -> Define cost of treatment harm and use NB (Calibration is important and affects NB)
2. Deal with resource constraint -> use flexible Lift Curve / PPV values for different PPCR (Discrimination Performance Metrics)

- What is hapenning today? (-> Which current strategy are you trying to beat? Treat All? Treat None? Baseline Model?)
1. Treat All / Treat None / Formal Tree Models.
