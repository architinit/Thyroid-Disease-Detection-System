# Thyroid-Disease-Detection-System
This repository contains a machine learning-based diagnostic system developed to automate the classification of thyroid conditions using clinical and demographic patient data. The system bridges the gap between traditional biochemical testing and automated clinical decision-making.

**📊 Project Overview**
Thyroid disorders often go undiagnosed due to the resource-intensive nature of traditional clinical evaluations. This project leverages ensemble learning to analyze complex patterns in patient records, providing a scalable and efficient solution for early intervention.

**Key Performance Metrics**
•	Best Model: Random Forest 
•	Testing Accuracy: 90.10% 
•	Precision: 0.90 
•	F1-Score: 0.90

**🛠️Tech Stack**
•	Language: Python 3.8+ 
•	Libraries: Scikit-learn (ML Algorithms), Pandas (Data Manipulation), NumPy (Numerical Analysis), Matplotlib/Seaborn (Visualization) 
•	Environment: Jupyter Notebook / Google Colab

** 🧬 Methodology & System Architecture**
The system follows a multi-stage pipeline designed for clinical reliability:
1.	Data Collection: Analyzed 3,200 patient records including hormone levels (TSH, T3, TT4), age, gender, and medical history.
2.	Preprocessing: Performed mean/median imputation for missing values, Min-Max scaling for normalization, and Label Encoding for categorical features .
3.	Model Selection: Evaluated four core algorithms:
3.	Model Selection: Evaluated four core algorithms:
   •	Random Forest: Highest performance due to its ability to handle complex feature interactions.
   •	Decision Tree: Strong performance (89.19%) but slightly prone to overfitting.
   •	KNN: Achieved 85.25% accuracy but showed sensitivity to data noise.
   •	SVM: Lower performance (61.42%) due to dataset complexity.

**📈 Analysis & Insights**
•	Feature Distribution: TSH values were found to be highly right-skewed, with extreme high outliers representing pathological conditions like hypothyroidism.
•	Feature Importance: Using Matplotlib/Seaborn, we visualized key hormone indicators to interpret model predictions for clinical use.




