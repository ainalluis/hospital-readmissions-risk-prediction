# Hospital Readmissions Risk Prediction

## Motivation
Hospital readmissions are a key indicator of healthcare quality and efficiency. Under the Centers for Medicare & Medicaid Services (CMS) Hospital Readmissions Reduction Program (HRRP), hospitals with excess readmissions may face financial penalties.

The motivation of this project is to understand which factors are associated with excess hospital readmissions and to build a predictive model capable of identifying hospitals at high risk. This can support proactive decision-making and targeted interventions to improve patient outcomes and reduce costs.


## Dataset
This project uses publicly available data from the **CMS Hospital Readmissions Reduction Program (HRRP)**, which includes hospital-level readmission metrics for selected conditions and procedures.


## Software Dependencies
The project was developed using Python and the following main libraries:

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  

All analysis and modeling are performed in a Jupyter Notebook.


## File Descriptions
- DSproject.ipynb: Main Jupyter notebook containing the full analysis, modeling, and results.
- README.md: Project documentation and overview.
- FY_2025_Hospital_Readmissions_Reduction_Program_Hospital.csv: Raw dataset used for the analysis.

## How to Interact with This Project
1. Clone the repository
2. Install the required Python libraries
3. Open the Jupyter notebook
4. Run the notebook cells sequentially to reproduce the analysis and results.

## Results Summary
This project demonstrates that hospital readmission risk can be effectively anticipated using hospital-level data.

Several classification models were evaluated, including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. Among these, Logistic Regression showed consistently strong performance while offering high interpretability, making it suitable for this use case. This model achieved aproximately an 98% of accuracy.

Key findings include:
- Hospitals with higher baseline readmission rates are significantly more likely to exceed expected readmission thresholds.
- Hospital size, measured by the number of discharges, is an important contributor to readmission risk.
- Geographic location and procedure type showed more limited influence compared to baseline risk metrics.

Overall, the results suggest that data-driven models can support early identification of hospitals at risk of excess readmissions, enabling more proactive and informed healthcare decision-making.

## Licensing

This project is provided for educational purposes only.
The dataset is publicly available and subject to CMS data usage guidelines.

## Authors
Aina Lluís Huelmo

## Acknowledgments
- Centers for Medicare & Medicaid Services (CMS) for providing the public dataset.
- Course instructors and materials for guidance on the data science process.
