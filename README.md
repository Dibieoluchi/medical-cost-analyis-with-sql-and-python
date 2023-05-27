# medical-cost-analyis-with-sql-and-python
i conducted a medical cost analysis with  a dataset obtained from kaggle , I performed data preprocessing, cleaning, visualization, and transformation using SQL and Python libraries. I also utilized predictive modeling techniques in Python to build a multiple linear regression model. Here are the key findings:

1. Correlation Matrix: The correlation matrix revealed the following associations with medical charges:



. Children: A very weak positive correlation with medical charges.


. Sex: A very weak positive correlation with medical charges.


. Age: A moderate correlation with medical charges.


. BMI: A weak correlation with medical charges.


. Smoking Habits: A strong correlation with medical charges.


2. Factors Impacting Medical Charges: The analysis suggests that being a smoker and increasing age are the two most influential factors associated with higher medical charges. Sex and BMI have a relatively weaker impact.

3. Model Performance: The multiple linear regression model achieved an R-squared score of 0.749, indicating that it effectively explains a significant portion of the variation in medical costs using the independent variables (age, sex, children, BMI, and smoking habits). This suggests a moderate-to-strong relationship between these factors and medical charges.

4. Prediction: When applying the model to new data, it predicted that a 35-year-old male smoker with an obesity-related BMI of 30 would have a medical charge of $30,863. This estimate exceeds the median average medical charge, supporting the analysis that smokers generally have higher medical costs. Additionally, being male, having a higher BMI, and smoking all contribute to the expected increase in medical charges.

These findings provide valuable insights into the factors influencing medical charges and can aid in understanding and predicting healthcare costs. As a healthcare data scientist, I aim to contribute to improving healthcare outcomes by leveraging data-driven analysis
