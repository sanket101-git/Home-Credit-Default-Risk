# Home-Credit-Default-Risk
A comprehensive case study on machine learning that centers on developing a prediction model by utilizing Home Credit Group's dataset to detect potential loan defaulters
*** 
### Introduction
Home Credit is an international consumer finance provider which operates in 9 countries. It provides point of sales loans, cash loans and revolving loans to underserved borrowers.

Due to poor or nonexistent credit history, a significant portion of the population finds it difficult to have their house loans authorized. This keeps them from being able to purchase the homes of their dreams and occasionally even pushes them to rely on other funding sources that could be unstable and have high-interest rates. On the other hand, choosing which applicants to qualify for housing loans is a significant challenge for banks and other financial lending organizations. Due to the possibility that borrowers with a lengthy credit history could still default on their loan and the possibility that some borrowers with a strong likelihood of repaying their debt may not have a lengthy enough credit history, credit histories are not always an adequate basis for making judgments.
***
### Business Problem
Home Credit is facing a substantial barrier in providing loans to individuals with insufficient or non-existent credit histories. This challenge hampers the company's mission of broadening financial inclusion and exposes this demographic to exploitation by untrustworthy lenders.
### Project Objective
The primary objective of this project is to develop a predictive analytics solution using a supervised learning methodology to assess the creditworthiness of loan applicants. The goal is to utilize a classification algorithm to predict whether a loan applicant is likely to repay or default on their loan obligations. To achieve this objective, we will leverage a diverse set of alternative data sources, including telco and transactional information, to build a robust model. The target variable for the supervised classification model will be binary, indicating whether the applicant is classified as capable of repayment or not. Through this project, we aim to provide a reliable tool for financial institutions to make informed lending decisions, ultimately minimizing default risks and optimizing their loan portfolios.
***
### Solution to the business problem.
The solution to the business problem at Home Credit revolves around developing a robust predictive analytics model using supervised learning and classification algorithms to assess credit default risk. By leveraging diverse alternative data sources, such as telco and transactional information, we aim to provide Home Credit with a tool to evaluate their clients' repayment capabilities more accurately. The project scope encompasses model development, validation, and integration, with a focus on maximizing predictive performance metrics like accuracy and ROC values. Through this analysis, we strive to identify the most effective model for assessing credit default risk, ultimately aiding Home Credit in mitigating potential losses and ensuring a secure and positive borrowing experience for their clients.
***
### Contribution to the project
In the project, my primary responsibility was conducting feature engineering and implementing the LG Boost model. Feature engineering involves identifying, selecting, and transforming relevant features from diverse alternative data sources to improve the predictive power of the model. This process required careful analysis of the data to extract meaningful insights and create new features that capture important patterns related to loan repayment behavior. Additionally, I was responsible for preprocessing the data and ensuring compatibility with the LG Boost algorithm.
Implementing the LG Boost model involved configuring and fine-tuning the hyperparameters of the algorithm to optimize its performance in predicting credit default risk. I utilized libraries such as LightGBM to train the model on the prepared dataset, iteratively adjusting parameters to achieve the best possible results.
***
### Business value of the solution.
Optimized Loan Portfolio: The solution allows Home Credit to optimize its loan portfolio by prioritizing applications with higher expected returns relative to their risk. By focusing on loans with favorable Risk-Adjusted Return on Capital (RAROC) values, Home Credit can maximize profitability while maintaining an acceptable level of risk.

Enhanced Profitability: Through better risk assessment and portfolio optimization, Home Credit can improve its overall profitability. By approving loans with higher RAROC values, the company can generate more revenue while minimizing the impact of defaults on its bottom line.

Customer Satisfaction and Trust: By leveraging data-driven insights to make more accurate lending decisions, Home Credit can provide a secure and positive borrowing experience for its customers. This fosters trust and loyalty among borrowers, enhancing customer satisfaction and retention.
***
### Data Modeling
We use the following Machine learning algorithms and built Classification models for our supervised classification task.

1) Random Forest
2) Logistic Regression
3) Extreme Gradient Boost
4) Light Gradient Boost

   ![image](https://github.com/sanket101-git/Home-Credit-Default-Risk/assets/59793183/23fd059d-6764-4214-a429-661940680293)

   AUC Score of all the models that were used


### Model Evaluation
Evaluated Classification models by Accuracy, Confusion Matrix, Precision, Recall, F1-Score, and ROC.

After comparing the performance of the above technique Light Gradient Boost performs the best.
![image](https://github.com/sanket101-git/Home-Credit-Default-Risk/assets/59793183/ad6be9cd-afcb-47ae-93f2-14f0a0becf01)

***
### Difficulties that were encountered

Prioritizing Relevant Features: One of the significant difficulties our group encountered was dealing with the immense volume of data due to the presence of numerous data files. This posed challenges during the feature engineering phase, making it difficult to make informed decisions about which features to include in our predictive model. The sheer volume of data made it time-consuming and computationally intensive to analyze and extract meaningful features that could effectively capture the nuances of credit default risk.

Resource Constraints: Limited resources, including computational power, posed challenges in scaling our analysis and implementing modeling techniques. Optimizing model training times and efficiently utilizing available resources was time-consuming.

***
### Learnings
I learned several valuable lessons that enriched my understanding of predictive analytics and its application in the financial domain. Some key takeaways include:

Data Preprocessing and Cleansing: I gained hands-on experience in data preprocessing and cleansing techniques, including handling missing values, outlier detection, and data transformation. I learned the importance of ensuring data quality and consistency to build reliable predictive models.

Feature Engineering: Dealing with a large volume of data highlighted the significance of feature engineering in extracting meaningful insights and improving model performance. I learned various feature selection and extraction techniques to identify relevant predictors and enhance the predictive power of the model.

Model Development and Evaluation: Through implementing machine learning algorithms such as LG Boost, I deepened my understanding of model development, parameter tuning, and evaluation. I learned how to assess model performance using appropriate metrics and interpret results to make informed decisions.








