ENTPD1_ML

Codes in Python, to implementation of diverse models of Machine Learning, trying to promote prognosis in People Living with HTLV

Divided intially in four scripts:

Exploratory data analysis
Defining the models and optimizing them for our data set
Evaluation of the predictive capacity of the models
Application of Explainable AI (XAI) methods

Notes/reminders:
Clinical data has been excluded (because they will still be extracted from the medical records, classifying the oligosymptomatic patients separately, allowing a better evaluation of the machine)

Version used in the code below:

Python version: 3.11.7
scikit-learn version: 1.2.2
imbalanced-learn version: 0.12.1
scikit-optimize version: 0.10.1

#Data used named as = cat2_df_clinic_ENTPD1.csv
Dictionary:

In column: SEX
M = 0
F = 1
In column: P-HAM/TSP
No myelopathy = 0
P-HAM/TSP = 1
Expression_CD39_Diplotypes:
3 = Genotypes associated with high expression of CD39
2 = Genotypes associated with moderate expression of CD39
1 = Genotypes associated with low expression of CD39

Age (Idade_clinica): Inclusion of the patient's age
Dermatologic problems (Dermatológicos):
1 = In case of the presence of dermatologic problems
0 = In the absence of dermatologic problems
Arthralgia (Artralgia):
1 = In case of the presence of arthralgia
0 = In the absence of arthralgia
Urinary symptoms (Comprometimento da função urinária):
1 = In case of the presence of urinary symptoms
0 = In the absence of urinary symptoms
Psychiatric symptoms (Sintomas psiquiátricos):
1 = In case of the presence of psychiatric symptoms
0 = In the absence of psychiatric symptoms
Lower limb pain (Dor MMII):
1 = In case of the presence of lower limb pain
0 = In the absence of lower limb pain
Paresthesia of the lower limbs / Paresis/weakness of the lower limbs (Parestesia MMII / Paresia/Fraqueza MMII):
1 = In case of the presence of paresthesia or paresis/weakness in the lower limbs
0 = In the absence of paresthesia or paresis/weakness in the lower limbs
Low back pain (Dor Lombar/Coluna):
1 = In case of the presence of low back pain
0 = In the absence of low back pain
Neuropathy of the upper limbs (Neuropatia MMSS):
1 = In case of the presence of upper limb neuropathy
0 = In the absence of upper limb neuropathy
Motor Function (Função Motora):
1 = In case of the presence of motor function impairment
0 = In the absence of motor function impairment
