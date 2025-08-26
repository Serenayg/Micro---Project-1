# Micro-Project 1  
**Heart Disease Dataset – Data Preparation**

In the first week of this project, the primary goal was to become familiar with the **Heart Disease dataset** and prepare it for further analysis. This step is critical because data quality directly impacts the performance of machine learning models.  

I started by importing **NumPy** (for linear algebra operations) and **Pandas** (for data manipulation and processing). Using these libraries, I explored the dataset to understand its structure and contents. I checked:  
- **Data types and non-missing values** → to ensure that variables were correctly recognized (numeric vs categorical).  
- **Missing values and duplicates** → to identify potential data quality issues.  
- **Summary statistics of numerical columns** → to understand the range, central tendency, and variability of key features.  

Next, I examined the **target variable (HeartDisease)** and confirmed that the dataset is relatively balanced:  
- `1 = 508` individuals diagnosed with heart disease  
- `0 = 410` individuals without heart disease  

Finally, I reviewed the **categorical variables** (e.g., Sex, ChestPainType, RestingECG, ST_Slope, ExerciseAngina) to better understand how they are distributed across the dataset. This step will guide future encoding and preprocessing decisions.  

By the end of Week 1, the dataset was well-understood and ready for the next phase of preprocessing. This foundation ensures that later steps, such as feature scaling and machine learning model training, will be built on a **clean and reliable dataset**.
