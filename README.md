# Machine Learning - Predicting Cardiovascular Disease
This project aims to analyze a dataset of 70,000 surveyed patients to identify correlations and predictors of Cardiovascular Disease (CVD). By performing exploratory data analysis and evaluating our selected Machine Learning models against performance metrics such as accuracy, precision, recall, and f1-score, we aim to uncover significant factors that influence the likelihood of having CVD. Specifically, our findings indicate that systolic and diastolic blood pressure, cholesterol levels, age, weight, and BMI are the most significant indicators of susceptibility to CVD.

# Dataset
The [dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset) used for this analysis consists of 70,000 patient records collected through surveys. Each record contains various attributes related to the patients' health, including blood pressure readings, cholesterol levels, age, weight, and the presence or absence of CVD. The dataset has been preprocessed to remove any inconsistencies or missing values to ensure accurate analysis.

# Goals
The primary objectives of this project are as follows:

Identify correlations: We aim to explore the relationships between different attributes and the presence of CVD. By analyzing the dataset, we can identify correlations that may provide insights into the underlying factors contributing to CVD.

Predictive modeling: Utilizing the dataset, we intend to develop predictive models that can estimate the likelihood of an individual having CVD based on various attributes such as blood pressure, cholesterol levels, age, and weight. These models will aid in early detection and prevention efforts.

Feature importance: By analyzing the dataset and employing statistical techniques, we seek to determine the most significant factors that contribute to the development of CVD. Understanding these factors can help healthcare professionals prioritize interventions and develop targeted prevention strategies.

# Analysis Process
The analysis process comprises the following steps:

Data cleaning: We thoroughly cleaned the dataset by removing any missing values, correcting inconsistencies, and addressing outliers. This step ensures the accuracy and reliability of our analysis.

Exploratory data analysis: We conducted an initial exploration of the dataset to gain insights into the distributions of various attributes and their relationships with the presence or absence of CVD. This helped us identify potential correlations and patterns.

Statistical analysis: Using appropriate statistical techniques such as correlation analysis, hypothesis testing, and regression models, we examined the relationships between different attributes and CVD. This allowed us to determine the significance of each attribute and identify predictors of CVD.

Model development: We developed predictive models using machine learning algorithms such as logistic regression, decision trees, or support vector machines. These models were trained on a subset of the dataset and evaluated using appropriate performance metrics to ensure their accuracy and reliability.

Interpretation and visualization: We presented our findings through clear and interpretable visualizations, including charts, graphs, and tables. These visual aids help communicate the relationships and patterns we discovered in the dataset.

## Interactive Interface
To provide a user-friendly experience and enable personalized risk assessment, we created an interactive interface. This interface allows users to input their characteristics, including relevant health attributes, and obtain an estimated diagnosis of their likelihood of having cardiovascular disease. By integrating the developed models, the interface will provide valuable insights and assist users in understanding their CVD risk profile.

# Results & Conclusion
Our analysis confirmed the significance of systolic and diastolic blood pressure, as well as obesity, in predicting the presence of cardiovascular disease (CVD). By considering features such as age, height, weight, gender, blood pressure, cholesterol, glucose levels, smoking status, alcohol intake, and physical activity, we achieved an accuracy of approximately 72% in predicting CVD using an artificial neural network (ANN) machine learning model.

However, it is important to highlight that this accuracy can be further improved through better data collection and the utilization of a larger dataset. By leveraging an ANN model, we can harness the power of complex non-linear relationships and patterns present in the data to enhance prediction accuracy. To maximize the potential of our model in the future, we recommend gathering data that is collected and entered by medical professionals. This approach can help minimize user bias and errors, ultimately contributing to the development of a more robust and reliable predictive model for CVD.
