# Applied_ML_Final
 
This project aims to predict the toxicity of drug compounds using machine learning models trained on Morgan fingerprints. By evaluating logistic regression, Ridge regression, Random Forest, and XGBoost, I identifed chemical substructures associated with toxicity and assessed each model’s performance and robustness. The best-performing model, Random Forest, achieved high accuracy and better balance between precision and recall. I tried using dimensionality reduction and feature engineering to improve the model, and cross- validation was used to obtain robust results.

The files are:
1. Data quality checks, Feature Matrix Generation: Loads the ClinTox dataset, computes Morgan fingerprints, and performs basic data validation.
2. Logistic_Regression,_Ridge_Feature_Engineering,_PCA: Trains baseline logistic and Ridge models, engineers features, and performs PCA.
3. Random_Forest_Feature_Generation,_XGBoost: Trains Random Forest and XGBoost models; compares feature importances.
4. Comparing_Performance,_Discussion: Summarizes performance metrics, visualizes results, and an interpretation of the result.
5. AppliedML_Final report

The dataset used in this project is the ClinTox dataset from MoleculeNet, managed by DeepChem. You can download it directly using DeepChem.
