# PerformancePrediction machine learning

This project implements a machine learning pipeline to identify and predict the key behavioral and demographic factors that influence student academic success. By training multiple classifiers on historical student data, the model determines which variables—such as classroom engagement or study habits—are the strongest predictors of final grades.

### **1. Data Overview**
The analysis is powered by a comprehensive dataset (CSV) containing diverse student profiles, featuring:
* **Demographics:** Nationality and Grade Level.
* **Engagement Metrics:** Number of times hands were raised and frequency of attendance.
* **Academic Habits:** Total hours studied and participation in discussion groups.



### **2. Machine Learning Methodology**
To ensure the highest predictive accuracy, the project evaluates and compares several **Supervised Learning Classifiers**, including:
* **Decision Trees / Random Forest:** To map the hierarchical importance of features.
* **Support Vector Machines (SVM):** For high-dimensional classification.
* **Logistic Regression:** To establish baseline correlations between habits and grades.

### **3. Data Engineering & Visualization**
The project utilizes advanced data modeling techniques to validate the results:
* **Feature Engineering:** Processing raw CSV data into a format suitable for ML models.
* **Correlation Heatmaps:** Visualizing the relationship between variables (e.g., how "attendance" correlates with "final marks").
* **Confusion Matrices:** Evaluating model performance by comparing predicted grades against actual results.
* **Performance Charts:** Graphical comparisons of accuracy across different ML models.


