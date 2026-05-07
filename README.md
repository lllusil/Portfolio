# Xinrui Li

#### Technical Skills: SQL, Excel, Python (pandas, matplotlib), R (ggplot2), Java, C++

## Education
- B.S., Data Science | University of Arizona (_May 2026_)

## Work Experience
**Data Analyst Intern @ Bank of China, Chongqing Branch (_July 2024 - September 2024_)**
- Wrote Python scripts to automatically extract 5,000+ potential loan customers, using cross-comparison to assist in controlling pre-loan access risks.
- Used SQL multi-table joins to extract customer deposit and loan details, cleaned and converted them to output standardized documents, ensuring compliance and completeness of files.
- Participated in pre-loan review and mid-loan follow-up, ensured zero errors in information transmission, extracted business metrics to form summaries, and improved approval efficiency.

## Projects

### DataFest Competition: Prostate Cancer Patient Diagnosis and Treatment Pathway Analysis
Integrated clinical data and cleaned SDOH variables, utilizing K-means to target the prostate cancer cohort and reconstructing it using time-series alignment technology. Initially applying MLR and missing dummy variables to diagnose data as MINAR, the linear model showed weak explanatory power. Subsequently, the XGBoost sparsity-aware algorithm was employed to increase the prediction AUC to 0.678, ultimately outputting regression coefficients using MLR to balance prediction performance and interpretability. This approach confirmed that unanswered questionnaires indicate informative missingness, identifying driving factors for medical dropout and assisting in early intervention.

![Prostate Cancer Pathway Analysis](/assets/img/prostate_cancer_analysis.jpg)

### Medical Insurance Cost Determinants Analysis
Based on over 1,300 medical insurance data points, this project eliminated multicollinearity via VIF, filtered non-significant features via F-test, and retained extreme features to support precise medical insurance cost pricing. Using MLR as a baseline, the model was upgraded to a Gamma GLM to address heteroscedasticity, significantly improving the robustness of cost predictions. Furthermore, the introduction of interaction term analysis revealed that obesity risks are amplified in smoking populations, enabling more precise pricing strategies for high-risk groups.

![Medical Insurance Cost Analysis](/assets/img/medical_insurance_analysis.jpg)

### Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM)
Utilized a Beta-GAMM model to customize 12-16 week testing windows for different pregnant women, effectively reducing associated risks and costs. By applying the EasyEnsemble framework, the average model accuracy was increased by 1.4 times, successfully resolving sample imbalance issues. Additionally, a conformal prediction mechanism was introduced to establish a three-tier triage strategy, ensuring zero missed diagnoses while effectively suppressing the false positive rate.

![CUMCM Modeling](/assets/img/cumcm_modeling.jpg)
