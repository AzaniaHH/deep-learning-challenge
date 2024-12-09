# Alphabet Soup Applicant Success Analysis
<br>

## Analysis Overview
The purpose of this project is to develop a deep learning model to predict the applicants most likely to achieve success. These applicants will then be selected for funding. By analyzing over 34,000 organizations that received funding from Alphabet Soup, the project aims to develop a predictive capability that will help Alphabet Soup optimize its funding.
<br>

## Results
### Data Processing
The data included application type, organization type, income, and outcome ("IS_SUCCESSFUL"). The target variable was outcome, specifically "IS_SUCCESSFUL". The varialbe that are features are APPLICATION TYPE, CLASSICATION, and AKS_AMT. Lastly, the "EIN" and "NAME variables were removed from the DataFrame because they were neither features nor targets. 
![image](https://github.com/user-attachments/assets/69ccf125-fb18-4562-bdb5-86aeb8d591b6)
<br>

### Compiling, Training, and Evaluating the Model
The neurons used were as follows:
•	Input Layer: Equal to the number of features (after preprocessing, such as one-hot encoding and scaling).
•	First Hidden Layer: 80 neurons were selected.
•	Second Hidden Layer: 30 neurons were used.
•	Output Layer: A single neuron for binary classification (IS_SUCCESSFUL).
![image](https://github.com/user-attachments/assets/1b1241a1-424d-42e5-b567-da97e63ca733)

![image](https://github.com/user-attachments/assets/bf640756-dc9c-4447-8402-4d8d9d1e71fa)

