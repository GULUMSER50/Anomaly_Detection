# Report for Anomaly Detection 

Project Title:
Anomaly Detection 

Objective:
The objective of this project is to perform anomaly detection and assessment on a diabetes dataset.

Information about the Dataset:

The dataset contains factors related to diabetes.

 Columns:
 0   Pregnancies               
 1   Glucose                   
 2   BloodPressure             
 3   SkinThickness            
 4   Insulin                   
 5   BMI                       
 6   DiabetesPedigreeFunction  
 7   Age                       
 8   Outcome                  
 
It comprises a total of 768 entries.
Initially, there is an imbalanced class distribution.
  
  Outcome.value_counts()
  0    500
  1    268

Data Processing and Cleaning Steps:

The dataset is read, and general information is reviewed.
Erroneous data in certain features are cleaned.
After cleaning erroneous data, the dataset is re-evaluated.

Anomaly Detection Steps:

One-Class SVM (Support Vector Machine):

The One-Class SVM model is applied to the dataset.
The model identifies observations deemed as anomalies.
Boxplots are used to visualize anomalies.

Isolation Forest:

The Isolation Forest model is applied to the dataset.
The model identifies observations deemed as anomalies.
Boxplots are used to visualize anomalies.

Results:

Anomalies detected by both models are visualized.
Common anomalies detected by SVM and Isolation Forest models are identified.
Common anomalies are predominantly associated with Insulin values.

Additional Notes:

Detailed visualizations and explanations are provided within the project.
Data cleaning steps are executed in accordance with the domain knowledge.
This report encompasses the general steps of the project and the obtained results. Further details and analyses can be added based on the complexity and objectives of the project.






