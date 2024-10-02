# HOSPITAL-READMISSION-ANALYSIS
This project focuses on analyzing hospital re-admissions for diabetes patients using the Hadoop MapReduce framework. Leveraging the Diabetes 130-US hospitals for years 1999-2008 dataset from Kaggle, we aim to identify patterns and factors contributing to the likelihood of patient readmission. The dataset contains over 100,000 records of hospital admissions, providing detailed information on patient
demographics, medical history, and treatment outcomes.
 
The project employs a two-phase Hadoop MapReduce approach. In the first phase, the data is preprocessed to filter and extract relevant attributes such as patient age, number of prior inpatient visits, and readmission status. The second phase performs an in-depth analysis of these attributes to determine correlations between patient demographics and readmission rates.
 
By utilizing the distributed processing capabilities of Hadoop, this project handles large volumes of data efficiently, making it possible to draw insights from the dataset at scale. The results of this analysis can be instrumental for healthcare providers in developing targeted interventions to reduce readmission rates among diabetes patients, ultimately improving patient outcomes and reducing healthcare costs.

#SUMMARY
This project utilizes Hadoop MapReduce to analyse hospital readmissions among
diabetes patients, using the Diabetes 130-US hospitals dataset. Key steps include
data preprocessing, extracting patient demographics, and analysing factors like age
and prior visits. Insights from this analysis aim to reduce readmission rates and
enhance healthcare outcomes.
 
Key findings include variations in readmission rates based on age and prior visits,
such as 30 out of 150 patients over 60 with 3 prior visits being readmitted. These
insights can inform strategies to reduce readmissions
