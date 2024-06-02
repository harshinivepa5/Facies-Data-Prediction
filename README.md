# Facies-Data-Prediction
## Prediction of Facies Data
The objective of this project is to predict facies values from well log data using machine learning algorithms, specifically for classification. The process begins with the collection of well log data from sensors, which is then transformed into a CSV format for easier analysis. Preprocessing steps, including feature selection, data cleaning, and outlier removal, ensure the quality of the input data. The dataset is divided into training and test sets, with well "C6" used as the test data. Multiple machine learning models, such as Random Forest, Logistic Regression, and XGBoost, are evaluated. The Random Forest model, with an R2 score of 0.868, is selected for its superior performance. When tested, the model achieves an accuracy of 73.38% in classifying facies, indicating its reliability and effectiveness. Implemented on the no-code platform Dataiku, this project demonstrates the capability of machine learning to accurately determine facies values, thus optimizing well log data analysis and operational efficiency.

Key Features and Functioning:
1. Data Collection:Well log data is collected from sensors and transformed into a CSV format, making it accessible for analysis.
2. Data Preprocessing:The data undergoes extensive preprocessing, including feature selection, cleaning, and outlier removal, to ensure high-quality input for the machine learning models.
3. Dataset Splitting:The dataset is divided into training and test sets, with well "C6" designated as the test data.
4. Model Evaluation:Various machine learning models, including Random Forest, Logistic Regression, and XGBoost, are evaluated to determine the best performer.
5. Model Selection:Random Forest is chosen based on its performance, achieving an R2 score of 0.868.
6. Model Training and Testing:The Random Forest model is trained and tested, yielding an accuracy of 73.38% on the test data, demonstrating its effectiveness in classifying facies.
