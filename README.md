# Advanced Math Project — Social Environment and Academic Performance
## Research question
How are students’ perceived levels of friend influence and their daily time spent with friends associated with academic performance?
## Research hypotheses
H₀ (Null hypothesis): There is no association between students' perceived level of friend influence and their GPA category. The variables are independent.
H₁ (Alternative hypothesis): There is an association between students' perceived level of friend influence and their GPA category. The variables are not independent.
Significance level: α = 0.05.
Since the chi-square test produced a p-value below 0.05, we reject H₀. However, Cramér's V ≈ 0.091 indicates that the association is weak.
## Dataset and source
This project uses the dataset accompanying the 2025 Data in Brief article, Dataset of factors affecting learning outcomes of students at the University of Education, Vietnam National University, Hanoi (Tran, Nguyen and Le).
The dataset contains 2,170 student records. It is available from Mendeley Data: https://data.mendeley.com/datasets/23ppcdbmhc/1
The Excel file is named Database paper.xlsx, and the analysis uses InfuenceF_Friends, Time_Friends, and GPA.
## Methods
1. Descriptive statistics and cross-tabulations.
2. Chi-square test of independence and Cramér's V.
3. Permutation test using 2,000 shuffles.
4. Three-variable heatmap comparing friend influence, time spent with friends, and higher GPA.
## Main findings
The chi-square statistic was approximately 71.48, with 16 degrees of freedom and a p-value below 0.05. Cramér's V was approximately 0.091, indicating a weak association. The permutation test also supported evidence of an association. These results do not establish causation.
## Repository files
The repository contains the Python notebook, three PDF graphs, README, and HTML website.
## Website
https://marielasimeonova.github.io/Advanced-math-project/
## Limitations
The data are observational and self-reported. Unequal group sizes, possible confounding factors, and non-random sampling limit the conclusions.

