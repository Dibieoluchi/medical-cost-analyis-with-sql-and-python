#Medical Cost Personal Dataset Analysis
#Overview
This project analyzes a small sample of the USA population's medical insurance costs based on various attributes such as age, sex, BMI, number of children, smoking habits, and region. The dataset is sourced from Kaggle and is used in the book "Machine Learning with R" by Brett Lantz. The analysis aims to identify the factors influencing medical charges and build a predictive model to estimate individual medical costs.

#Dataset Content
1.age: Age of primary beneficiary
2.sex: Gender of the insurance contractor (female, male)
3.bmi: Body mass index (kg/m^2)
4.children: Number of children covered by health insurance / Number of dependents
5.smoker: Smoking habits
6.region: Beneficiary's residential area in the US (northeast, southeast, southwest, northwest)
7.charges: Individual medical costs billed by health insurance

#Key Findings


#Correlation Matrix

The correlation matrix revealed the following associations with medical charges:

1.Children: Very weak positive correlation
2.Sex: Very weak positive correlation
3.Age: Moderate correlation
4.BMI: Weak correlation
5.Smoking Habits: Strong correlation
6.Factors Impacting Medical Charges
7.Being a smoker and increasing age are the two most influential factors associated with higher medical charges.
8.Sex and BMI have a relatively weaker impact.

#Model Performance
The multiple linear regression model achieved an R-squared score of 0.749, indicating a moderate-to-strong relationship between the independent variables (age, sex, children, BMI, and smoking habits) and medical charges.

#Prediction
Applying the model to new data, it predicted that a 35-year-old male smoker with an obesity-related BMI of 30 would have a medical charge of $30,863, exceeding the median average medical charge.


#Conclusion
These findings provide valuable insights into the factors influencing medical charges and can aid in understanding and predicting healthcare costs. As a healthcare data scientist, I aim to contribute to improving healthcare outcomes by leveraging data-driven analysis.

.
