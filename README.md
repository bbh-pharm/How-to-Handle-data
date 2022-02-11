# How to Handle data

## Outlier Detection
### - Simple ways
- Tukey fences (InterQuartile Range, IQR)
- Z-score
### - Automatic outlier detection
- [Isolation Forest (iForest)](https://github.com/bbh-pharm/How-to-Handle-data/blob/main/Outlier-detection/Isolation_Forest_(iForest).ipynb)
- [Local Outlier Factor (LOF)](https://github.com/bbh-pharm/How-to-Handle-data/blob/main/Outlier-detection/Local_Outlier_Factor_(LOF).ipynb)
- [Minimum Covariance Determinant (MCD)](https://github.com/bbh-pharm/How-to-Handle-data/blob/main/Outlier-detection/Minimum_Covariance_Determinant_(MCD).ipynb)
- [One Class Support Vector Machine (OCSVM)](https://github.com/bbh-pharm/How-to-Handle-data/blob/main/Outlier-detection/One_Class_Support_Vector_Machine_(OCSVM).ipynb)

## Data Imbalance problem

|        |Regression tasks | Classification tasks|
|--------|----------------|---------------------|
|Data level methods||**Random resampling** </br> - Random Over-Sampling </br> - Ramdom Under-Sampling </br> </br> **Synthetic sample** </br> - SMOTE (Synthetic Minority Over-sampling Technique </br> - Using GAN|
|Algorithm level methods|- Label Distribution Smoothing (LDS) </br> - Feature Distribution Smoothing (FDS) |**Sample weighting (Cost sensitive learning)** </br> - [Inverse of Number of Samples (INS)](https://github.com/bbh-pharm/How-to-Handle-data/blob/main/Class-Imbalance/Inverse_of_Number_of_Samples_(INS).ipynb) </br> - [Inverse of Square Root of Number of Samples (ISNS)](https://github.com/bbh-pharm/How-to-Handle-data/blob/main/Class-Imbalance/Inverse_of_Square_Root_of_Number_of_Samples_(ISNS).ipynb) </br> - [Effective Number of Samples (ENS)](https://github.com/bbh-pharm/How-to-Handle-data/blob/main/Class-Imbalance/Effective_Number_of_Samples_(ENS).ipynb) </br></br> **Two stage training**|


<br></br>   
**Reference**   
- https://www.youtube.com/watch?v=CU2GF0du36o
