## Diabetes-Prediction
Objective
The objective of this project is to build a predictive model that can accurately classify whether a patient has diabetes or not based on various symptoms and conditions often associated with diabetes. The target column for prediction is labeled 'class' and has two possible values: 'Positive' (indicating the presence of diabetes) and 'Negative' (indicating the absence of diabetes).

# Dataset
The dataset consists of multiple features related to symptoms and conditions associated with diabetes. Each row represents a patient, and the columns are as follows:

-Age: Age of the patient
-Gender: Gender of the patient (Male/Female)
-Polyuria: Excessive urination (Yes/No)
.Polydipsia: Excessive thirst (Yes/No)
.Sudden weight loss: Sudden weight loss (Yes/No)
.Weakness: General weakness (Yes/No)
.Polyphagia: Excessive hunger (Yes/No)
.Genital thrush: Genital thrush (Yes/No)
.Visual blurring: Visual blurring (Yes/No)
.Itching: Itching (Yes/No)
.Irritability: Irritability (Yes/No)
.Delayed healing: Delayed healing of wounds (Yes/No)
.Partial paresis: Partial paresis (Yes/No)
.Muscle stiffness: Muscle stiffness (Yes/No)
.Alopecia: Hair loss (Yes/No)
.Obesity: Obesity (Yes/No)
.Class: Diabetes class (Positive/Negative)

1. Importing the libraries and loading the dataset
2. Exploratory Data Analysis

   
  # Univariate and Bivariate Analysis
Univariate Analysis
Univariate analysis involves examining each variable in the dataset separately. Here, we'll look at the distribution of numerical and categorical variables.
Bivariate Analysis
Bivariate analysis involves examining the relationship between two variables.

ROC Curves: The ROC curves help visualize the trade-off between sensitivity (recall) and specificity for different models. The closer the curve follows the left-hand border and then the top border of the ROC space, the more accurate the test.

Confusion Matrices: These matrices provide a detailed breakdown of the model's performance by showing the counts of true positive, true negative, false positive, and false negative predictions. This helps in understanding the types of errors made by the models.

By analyzing these visualizations, we can see that the Random Forest and Gradient Boosting models perform exceptionally well, achieving near-perfect accuracy and ROC AUC scores. On the other hand, the SVM model shows lower performance, especially in terms of recall for the negative class.

 
