**Article**: Combining machine learning and dynamic system techniques to early detection of respiratory outbreaks in routinely collected primary healthcare registries - BMC Medical Research Methodology

## MMAING Algorithm  

This repository contains the notebook "Algorithm_MMAING.ipynb" for outlier detection in primary healthcare data, utilizing various machine learning techniques alongside an epidemic propagation dynamics model. The primary objective is to identify unusual patterns in healthcare visits related to respiratory syndromes across different immediate geographic regions.  

## Features  

- Loading and processing of healthcare data.  
- Application of outlier detection methods:  
  - Isolation Forest  
  - One-Class SVM  
  - Local Outlier Factor  
  - Copula-Based Outlier Detection  
  - Time-Varying Reproduction Number  
- Saves the results.  

## Dependencies  

To run the notebook, the following Python libraries must be installed:  

pip install pandas numpy scikit-learn pyod joblib pyarrow


## Usage  

1. Available in the repository:  

https://github.com/cidacslab/MMAING  

2. Run the notebook "Algorithm_MMAING.ipynb" in a Jupyter Notebook or Jupyter Lab environment.  

## Code Structure  

- Data Preparation: Grouping by municipality and Immediate Geographic Region (RGI).  
- Model Application:Training and applying the models.  
-Analysis: Generating results in ".csv" format.  

## Authors  
Dérick G. F. Borges (1) and Eluã R. Coutinho (2)  
(1) Physics Institute, Federal University of Bahia (UFBA), Salvador, Bahia, Brazil.  
(2) Department of Computing, Fluminense Federal University (UFF), Rio das Ostras, Rio de Janeiro, Brazil.  

