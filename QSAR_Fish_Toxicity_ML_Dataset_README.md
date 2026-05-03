Assignment dataset file: «QSAR_Fish_Toxicity_ML_Assignment_Dataset_Kabir_Faizul.csv» file provided by BIGM with the following varibale:

**Problem 2: Regression Problem**
The QSAR (Quantitative Structure–Activity Relationship) Fish Toxicity dataset is designed to develop regression models predicting acute aquatic toxicity (LC50) of chemicals toward the fathead minnow (Pimephales promelas). It comprises 908 chemical compounds, each characterized by six molecular descriptors, with the target variable being the LC50 value, expressed as –log(mol/L). 

**Dataset Description:**
* Purpose: To predict acute toxicity levels of chemicals to Pimephales promelas using molecular descriptors.
* Size: 908 chemical compounds.
* Target Variable: LC50 (–log(mol/L)), representing the concentration that causes death in 50% of test fish over a specified period. 

| VARIABLE   | DESCRIPTION  |  TYPE |
|------------|--------------|-------|
| CIC0       | Neighborhood symmetry index | Numeric |
| SM1_Dz(Z)  | 2D matrix-based descriptor derived from the molecular graph| Numeric| 
| GATS1i     | 2D Geary autocorrelation descripitor       | Numeric|
| NdsCH      | Count of unsaturated sp2 carbon atoms of the type =CH–   | Integer| 
| NdssC      | Count of unsaturated sp2 carbon atoms of the type =C     | Integer| 
| MLOGP      | Octanol–water partition coefficient (log P) calculated via the Moriguchi model | Numeric| 
| LC50       | –log(mol/L) of the concentration causing 50% mortality in test fish          | Numeric|
