# Case-Study, Telecom-Churn Project

## Extracting insights through data
This project is a case study for data analysis and prediction, which was carried out in order to apply and showcase my knowledge acquired over the past few weeks. The main objective is to understand which factors lead customers to leave the company and how we can predict and prevent this.

### Data Used
The data used in this project was imported from the Kaggle platform, whose reliability is already evident, and includes information about customers, their plans, service usage, and whether they left the company or not. The data is confidential and has been anonymized to ensure customer privacy.

### Technologies Used
The main technologies used in this project were:

- Python
- Pandas
- Matplotlib
- Scikit-learn

## Exploratory Data Analysis
Before starting modeling, an exploratory data analysis was carried out to better understand the characteristics of the customers and identify patterns or trends in the data. The following variables were analyzed:

- Demographics: gender, number of dependents, etc.
- Contracted plans: type of plan, contract duration, monthly value, etc.
- Service usage: calls, internet, etc.
- Churn: whether the customer left the company or not.

## Churn Prediction

Based on the exploratory data analysis, we were able to deepen our analysis by applying a robust machine learning model called Logistic Regression, which, through the inputs received from our DataFrame, was able to predict the target variable Churn.

We used additional algorithms in order to enhance the accuracy of our model:

- SelectKBest, for feature selection.
- RandomSearchCV, for hyperparameter tuning.
etc..
Finally, using cross-validation techniques and performance metrics such as AUC-ROC, precision, recall, and Confusion Matrix, we obtained a concise visualization of our model, allowing for its possible applicability.

## Results and Conclusions

Based on the exploratory data analysis and churn prediction, we identified the main factors that lead customers to leave the company. Strategies and recommendations were developed to reduce churn, such as offering discounts on long-term plans and improving the quality of customer service.



Clone this repository to your local machine.
Install the necessary dependencies using the requirements.txt file.
Execute the file to reproduce the project steps.

### Contribution

This project is open to contributions. If you have any suggestions or want to contribute code, feel free to fork the repository and submit a pull request.

### Contact

If you have any questions or comments about this project, please contact me through my GitHub profile or send an email to my email address topperandrade@hotmail.com.

