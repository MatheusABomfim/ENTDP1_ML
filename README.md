ENTPD1_ML: Machine Learning for Prognosis in People Living with HTLV
This repository contains Python scripts for implementing various Machine Learning models aimed at predicting prognosis in People Living with HTLV.

Project Structure
The project is initially divided into four main scripts:
- Exploratory Data Analysis (EDA): Initial data exploration and preprocessing.
- Model Selection and Optimization: Defining and optimizing machine learning models.
- Model Performance Evaluation: Assessing the predictive capability of the models.
- Explainable AI (XAI) Application: Applying XAI techniques to interpret the model's predictions.


Notes & Reminders
Clinical data has been excluded since it is yet to be extracted from medical records.
Once available, oligosymptomatic patients will be classified separately to enhance model performance.
Environment & Dependencies
The code was developed using the following versions:


Python version: 3.11.7  
Libraries:  
- scikit-learn: 1.2.2  
- imbalanced-learn: 0.12.1  
- scikit-optimize: 0.10.1  
Dataset Information
The dataset used is named: cat2_df_clinic_ENTPD1.csv.

Data Dictionary:

Categorical Variables
SEX (Gênero)
0 = Male
1 = Female

P-HAM/TSP (PROVAVEL_HAM/TSP)
0 = No myelopathy
1 = P-HAM/TSP

Expression_CD39_Diplotypes
3 = Genotypes associated with high CD39 expression
2 = Genotypes associated with moderate CD39 expression
1 = Genotypes associated with low CD39 expression

Age (Idade_clinica) = Patient's age in years.

Binary Clinical Symptoms (0 = Absence / 1 = Presence)

Dermatologic problems (Dermatológicos)
1 = Presence of dermatologic problems
0 = Absence of dermatologic problems
Arthralgia (Artralgia)

1 = Presence of arthralgia
0 = Absence of arthralgia
Urinary symptoms (Comprometimento da função urinária)

1 = Presence of urinary symptoms
0 = Absence of urinary symptoms
Psychiatric symptoms (Sintomas psiquiátricos)

1 = Presence of psychiatric symptoms
0 = Absence of psychiatric symptoms
Lower limb pain (Dor MMII)

1 = Presence of lower limb pain
0 = Absence of lower limb pain
Paresthesia of the lower limbs / Paresis/weakness of the lower limbs (Parestesia MMII / Paresia/Fraqueza MMII)

1 = Presence of paresthesia or paresis/weakness in the lower limbs
0 = Absence of paresthesia or paresis/weakness in the lower limbs
Low back pain (Dor Lombar/Coluna)

1 = Presence of low back pain
0 = Absence of low back pain
Neuropathy of the upper limbs (Neuropatia MMSS)

1 = Presence of upper limb neuropathy
0 = Absence of upper limb neuropathy
Motor Function (Função Motora)

1 = Presence of motor function impairment
0 = Absence of motor function impairment
