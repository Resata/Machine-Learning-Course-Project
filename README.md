## 🚕 Automatidata – Predicting Generous Tippers Using Machine Learning (Course 6)

A machine learning classification project completed as part of Course 6: The Nuts and Bolts of Machine Learning in the Google Advanced Data Analytics program.
This project builds and evaluates tree-based models to predict whether a NYC Yellow Taxi customer is a generous tipper (≥ 20% tip). The analysis supports decision-making for taxi drivers while explicitly considering ethical implications and model limitations.


### 📌 Project Objectives
* Reflect on the ethical implications of predicting tipping behavior


* Engineer features relevant to tipping generosity


* Define a binary target variable based on tip percentage


* Build and tune tree-based classification models


* Compare model performance using appropriate evaluation metrics


* Interpret results in a real-world business context




### 🧰 Technologies Used
* Python 3


* pandas, NumPy


* scikit-learn


* XGBoost


* matplotlib


* Jupyter Notebook



### 📊 Key Insights
* The dataset is nearly balanced, with slightly more than half of riders classified as generous tippers.


* The Random Forest model slightly outperformed XGBoost on test data.


* Final Random Forest performance:


F1 score ≈ 0.72


Accuracy ≈ 0.69


* The model produces more false positives than false negatives, meaning it sometimes predicts generosity where it does not occur — a concern for driver expectations.


* Feature importance analysis shows that temporal patterns and trip-related attributes are strong predictors of tipping behavior.

