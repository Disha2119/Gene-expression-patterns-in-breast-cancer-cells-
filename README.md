Gene Expression Analysis of Breast Cancer Cells
This project explores gene expression profiles in breast cancer cell lines to identify biomarkers associated with drug resistance. Using statistical analysis and machine learning techniques, the goal is to distinguish between drug-sensitive and drug-resistant breast cancer cells based on gene expression data.

📌 Project Objective
To investigate whether gene expression patterns in breast cancer cells differ between drug-resistant and drug-sensitive groups, and to determine if machine learning models can predict drug resistance based on gene expression data.

🧬 Dataset
Source: kaggle.com

Cell lines: BAS, HS578T, MCF7, MDA-MB-231

Columns included:

Gene: Gene symbols

Cell Line: Name of the breast cancer cell line

p-value: Statistical significance of expression change (filtered to include only genes with p < 0.05)

logFC: Log2 fold change in expression between resistant and control cells

🔬 Methodology
Data Preprocessing

Filtered genes by p-value < 0.05

Normalized logFC values

Labeled cell lines into drug-sensitive and drug-resistant groups

Exploratory Data Analysis (EDA)

Visualized expression patterns using boxplots and heatmaps

Compared logFC distributions across groups

Feature Selection

Identified genes with distinct expression changes between groups

Selected most informative genes based on statistical testing

Model Development

Used a Random Forest classifier to predict drug resistance

Split dataset into training and test sets

Evaluated using accuracy, precision, recall, F1 score, and ROC-AUC

Biological Interpretation

Investigated top genes contributing to resistance prediction

Cross-referenced findings with literature on drug resistance mechanisms

🛠 Tools & Libraries
Python

Pandas, NumPy – Data manipulation

Seaborn, Matplotlib – Visualization

Scikit-learn – Machine learning and model evaluation

SciPy, Statsmodels – Statistical analysis

✅ Results
The Random Forest model was able to predict drug resistance with good accuracy.

Identified key genes with significant roles in resistance, which may serve as potential biomarkers or therapeutic targets.

📚 Insights & Implications
Gene expression profiles can effectively distinguish between drug-sensitive and resistant breast cancer cells.

This analysis highlights the potential of machine learning in cancer research and personalized medicine.
