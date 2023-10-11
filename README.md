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

## Results

**1. Understanding Churn:**
   Through extensive data analysis and churn predictions, we've identified the key factors influencing customer attrition. These findings serve as critical insights for decision-making and guiding our service enhancements.

**2. Promoting Long-Term Contracts:**
   Based on our analysis, we recommend encouraging long-term contracts to significantly reduce churn. Two-year contracts have proven effective. This can be achieved by offering enticing discounts or exclusive benefits for extended contracts. Quality customer service and personalized support for long-term customers further foster loyalty and contract renewals.

**3. Enhancing Fiber Optic Internet Quality:**
   Our analysis reveals that Fiber optic InternetService users have a higher churn probability. Therefore, it's imperative to improve service quality and communication with these clients. Offering incentives or promotions can help retain these customers effectively.

**4. Addressing Senior Customer Needs:**
   Senior customers exhibit a higher churn rate than other age groups. Focusing on improved customer experiences and tailored services for this segment can boost retention.

**5. Encouraging Technical Support and Online Security Services:**
   Logistic regression analysis highlights that customers lacking Techsupport and OnlineSecurity services experience higher churn rates. It's advisable to promote customer sign-ups for these services through targeted marketing campaigns, emphasizing their significance and benefits.

**6. Promoting Automatic Payments:**
   The convenience of automated payments minimizes the likelihood of late fees and dissatisfaction leading to churn. Promoting auto-payment options and emphasizing their advantages improves retention rates.

## Conclusion

In conclusion, this analysis provides valuable insights into reducing churn and enhancing customer retention. These recommendations can guide strategic decisions, and they reflect our commitment to delivering exceptional service to our customers. We encourage further discussions and actions based on these findings to improve our business performance.

Feel free to reach out if you have any questions or need further information.


Clone this repository to your local machine.
Install the necessary dependencies using the requirements.txt file.
Execute the file to reproduce the project steps.

### Contribution

This project is open to contributions. If you have any suggestions or want to contribute code, feel free to fork the repository and submit a pull request.

### Contact

If you have any questions or comments about this project, please contact me through my GitHub profile or send an email to my email address topperandrade@hotmail.com.

